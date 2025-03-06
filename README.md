# mp3extra

`mp3extra` is a simple CLI tool for embedding images and lyrics into MP3 files.

## Features
- Add album art (image) to MP3 files
- Embed lyrics (supports ID3 tags)
- Simple command-line interface
- Batch processing for multiple files
- Automatic image and lyrics fetching

## Installation

```sh
go install github.com/mattn/mp3extra@latest
```

## Usage

### Embed an image
```sh
mp3extra -image cover.jpg song.mp3
```

### Automatically fetch and embed an image
```sh
mp3extra -image auto song.mp3
```

### Embed lyrics
```sh
mp3extra -lyrics lyrics.lrc song.mp3
```

### Automatically fetch and embed lyrics
```sh
mp3extra -lyrics auto song.mp3
```

### Embed both image and lyrics
```sh
mp3extra -image cover.jpg -lyrics lyrics.lrc song.mp3
```

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a. mattn)

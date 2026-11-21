# YouTube MP3 Downloader and Editor

Convert YouTube tracks to MP3, find verified 1000×1000 album artwork, and edit ID3 metadata tags locally in your browser.

## Features

- **YouTube MP3 Downloader Frame:** Access `ytmp3s.pl` directly inside a compact embedded frame to convert tracks before loading them into the editor.
- **1000×1000 Album Artwork Finder:** Search iTunes for verified `1000×1000` covers, extract and clean video titles from YouTube URLs via oEmbed, filter out `Alt/Noisy` releases, and optionally fill blank `Year` and `Genre` fields.
- **MP3 ID3 Tag Editor:** Read existing ID3v2.x / ID3v1 tags (or guess `Song Name` and `Artist` from messy filenames), preview audio, and edit `TIT2`, `TPE1`, `TALB`, `TPE2`, `TRCK`, `TPOS`, `TYER`, `TCON`, `TCOM`, `TBPM`, `COMM`, `USLT`, and `APIC` cover art.
- **Queue & Helpers:** Load multiple MP3 files into a switchable queue, apply shared album/artist/year/genre/cover values across queued tracks, format text fields in Title Case, and download standalone cover images.
- **Custom Export Filename & Shortcuts:** Default exported `.mp3` filenames to the song name (or enter a custom filename), use `Ctrl/Cmd + Enter` to export, press `Esc` to clear status messages, and toggle between light and dark themes.

## How to Run Locally

1. Download or clone this repository.
2. Open the HTML file in any modern web browser.

## Privacy & Data

All MP3 decoding, ID3 tag reading/writing, and theme preferences run locally in your browser — your audio files and tags are not uploaded to a server for editing. Artwork searches and YouTube title lookups make requests directly to iTunes and YouTube oEmbed from your browser.

# Torrent File Decoder

Deconstruct torrent files and generate magnet URIs for BitTorrent in your web browser with a bit of JavaScript.

The magnet URI this tool generates consists of a BitTorrent info hash, a name and maybe a few BitTorrent tracker URLs. The BitTorrent info hash is hex-encoded since Base32-encoding is no longer used.

This simple conversion tool has not been written with any error handling in mind. It may only work with valid torrent files.

Libraries for encoding bencoded data and generating SHA-1 hashes are borrowed from [nutbread](https://github.com/nutbread/t2m).

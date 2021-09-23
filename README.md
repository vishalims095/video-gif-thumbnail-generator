# Convert Video to gif or thumbnail

## Installation

Use the package manager npm to install.

## Don't forget to craete a "thumbnail" folder because all files get stored in thumbnail folder

```bash
npm i video-gif-thumbnail-generator
```
## Usage

```javascript
const timeZone = require('video-gif-thumbnail-generator')
```

```
create Thumbnail
```
1. timeZone.convertToThumbnail('url') //url should be any local file or any live video url

```
create GIF
```
1. timeZone.convertToGIF('url') //url should be any local file or any live video url

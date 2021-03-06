# waifu.pics

An unofficial API wrapper for [Waifu.pics](https://waifu.pics/docs) for easy to use.

# Why?
1. Easy to use
2. Fast data response
3. No external module
4. 100% coverage of waifu.pics api

# Category and endpoints

There are two categories of this API `SFW` and `NSFW`.

SFW Endpoints: `waifu`, `neko`, `shinobu`, `megumin`, `bully`, `cuddle`, `cry`, `hug`, `awoo`, `kiss`, `lick`, `pat`, `smug`, `bonk`, `yeet`, `blush`, `smile`, `wave`, `highfive`, `handhold`, `nom`, `bite`, `glomp`, `slap`, `kill`, `kick`, `happy`, `wink`

NSFW Endpoints:  `waifu`, `neko`, `trap`, `blowjob`

(Note: `waifu` exists in two versions first one SFW and second one NSFW, if you call getNSFWImage and select endpoint to waifu it'll send NSFW waifu.)

## Usage

```js
const { getSFWImage } = require('waifu.pics-wrapper');

getSFWImage('waifu').then(result => {
    console.log(result);
}).catch(e => console.log(e));
```

## License

Refer to the [license](https://github.com/MathInDOS/waifu.pics-wrapper/edit/main/LICENSE) file.

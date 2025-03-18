## For Termux/Ubuntu/SSH User

```bash
pkg update && pkg upgrade
pkg install git -y
pkg install nodejs-lts
pkg install ffmpeg -y
git clone https://github.com/xziyyy/clairity.git
cd clairity
npm install
```

[RECOMMENDED INSTALL ON TERMUX]
```bash
pkg install yarn
yarn
```

Run
```bash
npm start
```
Editing on Termux
```bash
npm install mc -y
mc
```

edit file in ./media/settings/config.js
```bash
global.botname = "Guhh Neverheartless" // bot name
global.ownerNumber = [`${global.6285238753330}`,'no2','no3'] // no owner can access all features
global.email = 'GuhhBotz@gmail.com' // leave blank if you don't have one
global.web = 'https://' // leave blank if you don't have one
global.location = 'Malang, Jawa Timur, Indonesia' // fill in your area or place of residence if you don't want to leave it blank
global.packname = 'Guhhputraa' // wm on the sticker
global.author = 'created by Guhh Neverheartless' // wm on the sticker
```

License: [MIT](https://choosealicense.com/licenses/mit/)

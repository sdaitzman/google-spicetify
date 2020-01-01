# google-spicetify
Spotify with Google style

*** Sam's fork instructions ***
1. [Install Spicetify](https://github.com/khanhas/spicetify-cli/wiki/Installation)
2. Follow [Spicetify setup instructions](https://github.com/khanhas/spicetify-cli/wiki/Basic-Usage) (`$ spicetifty` to generate config, `$ spicetify backup apply enable-devtool` to initialize and establish a safe backup). From now on, you can run `$ spicetify update` to apply any changes you make.
3. [Download this folder as zip](https://github.com/sdaitzman/google-spicetify/archive/master.zip) and extract it
4. Copy the resulting folder to your Spicetify Themes folder (you can use `$ spicetify path` and [this page](https://github.com/khanhas/spicetify-cli/wiki/Customization#themes) to help find the right folder).
5. Set the following fields in your config.ini:
```ini
current_theme    = google-spicetify
color_scheme     = SamSpotifyLight
```


# EVERYTHING BELOW IS FROM ORIGINAL VERSION

## Previews
#### Base
<img src="https://i.imgur.com/qguGx46.png" alt="img" align="center" width="600px">

#### Gow
<img src="https://i.imgur.com/XBnjRgk.png" alt="img" align="center" width="600px">

#### Dark
<img src="https://i.imgur.com/k6cIQik.png" alt="img" align="center" width="600px">

## How to install
1. Install [spicetify-cli](https://github.com/khanhas/spicetify-cli) and make sure it applies default theme succesfully.
2. Run these commands:
  
**Linux and MacOS** in Bash:
```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/khanhas/google-spicetify
```

**Windows** in Powershell:
```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/khanhas/google-spicetify
```

3. Finally, run:
```
spicetify config current_theme google-spicetify
spicetify apply
```

There are 4 color schemes you can choose: `Base`, `Dark`, `Gow`, `Spotify`. Change scheme with commands:
```
spicetify config color_scheme <scheme name>
spicetify apply
```

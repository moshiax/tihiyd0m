
## Search Syntax:

```(path:*.{File_extension1} OR path:*.{File_extension-N}) AND ({Keyname1} OR {Keyname-N}) AND (({Signature/pattern1} OR {Signature/pattern-N}) AND ({PlatformTag1} OR {PlatformTag-N}))```

**1. OpenAI API keys**

```(path:*.xml OR path:*.json OR path:*.properties OR path:*.sql OR path:*.txt OR path:*.log OR path:*.tmp OR path:*.backup OR path:*.bak OR path:*.enc OR path:*.yml OR path:*.yaml OR path:*.toml OR path:*.ini OR path:*.config OR path:*.conf OR path:*.cfg OR path:*.env OR path:*.envrc OR path:*.prod OR path:*.secret OR path:*.private OR path:*.key) AND (access_key OR secret_key OR access_token OR api_key OR apikey OR api_secret OR apiSecret OR app_secret OR application_key OR app_key OR appkey OR auth_token OR authsecret) AND ("sk-" AND (openai OR gpt)) AND (/sk-[a-zA-Z0-9]{48}/ AND (openai OR gpt))```

**2. Telegram API Key

```/telebot_token=\d+/ OR /TELEBOT_TOKEN=\d+/ OR /telegram_bot_token=\d+/ OR TELEGRAM_BOT_TOKEN=\d+ OR /telegram_token=\d+/ OR /TELEGRAM_TOKEN=\d+/ OR /telegram_api_key=\d+/ OR /TELEGRAM_API_KEY=\d+/ OR /telegram_secret=\d+/ OR /TELEGRAM_SECRET=\d+/ OR telebot_key=\d+ OR TELEBOT_KEY=\d+ OR телебот_токен=\d+ OR bot_token=\d+```

**3. Github OAuth/App/Personal/Refresh Access Token**

```(path:*.xml OR path:*.json OR path:*.properties OR path:*.sql OR path:*.txt OR path:*.log OR path:*.tmp OR path:*.backup OR path:*.bak OR path:*.enc OR path:*.yml OR path:*.yaml OR path:*.toml OR path:*.ini OR path:*.config OR path:*.conf OR path:*.cfg OR path:*.env OR path:*.envrc OR path:*.prod OR path:*.secret OR path:*.private OR path:*.key) AND (access_key OR secret_key OR access_token OR api_key OR apikey OR api_secret OR apiSecret OR app_secret OR application_key OR app_key OR appkey OR auth_token OR authsecret) AND (("ghp_" OR "gho_" OR "ghu_" OR "ghs_" OR "ghr_") AND (Github OR OAuth))```

**4. Google API key**

```(path:*.xml OR path:*.json OR path:*.properties OR path:*.sql OR path:*.txt OR path:*.log OR path:*.tmp OR path:*.backup OR path:*.bak OR path:*.enc OR path:*.yml OR path:*.yaml OR path:*.toml OR path:*.ini OR path:*.config OR path:*.conf OR path:*.cfg OR path:*.env OR path:*.envrc OR path:*.prod OR path:*.secret OR path:*.private OR path:*.key) AND (access_key OR secret_key OR access_token OR api_key OR apikey OR api_secret OR apiSecret OR app_secret OR application_key OR app_key OR appkey OR auth_token OR authsecret) AND (AIza AND Google)```

**5. Square OAuth/access token**

```(path:*.xml OR path:*.json OR path:*.properties OR path:*.sql OR path:*.txt OR path:*.log OR path:*.tmp OR path:*.backup OR path:*.bak OR path:*.enc OR path:*.yml OR path:*.yaml OR path:*.toml OR path:*.ini OR path:*.config OR path:*.conf OR path:*.cfg OR path:*.env OR path:*.envrc OR path:*.prod OR path:*.secret OR path:*.private OR path:*.key) AND (access_key OR secret_key OR access_token OR api_key OR apikey OR api_secret OR apiSecret OR app_secret OR application_key OR app_key OR appkey OR auth_token OR authsecret) AND (("sq0atp-" OR "sq0csp-") AND (square OR OAuth))```

**6. Shopify shared secret, access token, private/custom app access token**

```(path:*.xml OR path:*.json OR path:*.properties OR path:*.sql OR path:*.txt OR path:*.log OR path:*.tmp OR path:*.backup OR path:*.bak OR path:*.enc OR path:*.yml OR path:*.yaml OR path:*.toml OR path:*.ini OR path:*.config OR path:*.conf OR path:*.cfg OR path:*.env OR path:*.envrc OR path:*.prod OR path:*.secret OR path:*.private OR path:*.key) AND (access_key OR secret_key OR access_token OR api_key OR apikey OR api_secret OR apiSecret OR app_secret OR application_key OR app_key OR appkey OR auth_token OR authsecret) AND (("shpss_" OR "shpat_" OR "shpca_" OR "shppa_") AND "Shopify")```

**7. Slack Token**

```(path:*.xml OR path:*.json OR path:*.properties OR path:*.sql OR path:*.txt OR path:*.log OR path:*.tmp OR path:*.backup OR path:*.bak OR path:*.enc OR path:*.yml OR path:*.yaml OR path:*.toml OR path:*.ini OR path:*.config OR path:*.conf OR path:*.cfg OR path:*.env OR path:*.envrc OR path:*.prod OR path:*.secret OR path:*.private OR path:*.key) AND (access_key OR secret_key OR access_token OR api_key OR apikey OR api_secret OR apiSecret OR app_secret OR application_key OR app_key OR appkey OR auth_token OR authsecret) AND (xox AND Slack)```

**8. Camera in Google**
| **Запрос 1** | **Запрос 2** | **Запрос 3** | **Запрос 4** | **Запрос 5** | **Запрос 6** | **Запрос 7** | **Запрос 8** |
|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|
| inurl:”ViewerFrame?Mode=” | intitle:Axis 2400 video server | inurl:/view.shtml | intitle:”Live View / – AXIS” | inurl:ViewerFrame?Mode=Refresh | inurl:axis-cgi/jpg | inurl:axis-cgi/mjpg (motion-JPEG) | inurl:view/indexFrame.shtml |
| inurl:view/index.shtml | intitle:”live view” intitle:axis | intitle:liveapplet | allintitle:”Network Camera NetworkCamera” | intitle:axis intitle:”video server” | inurl:LvAppl | intitle:”EvoCam” inurl:”webcam.html” | intitle:”Live NetSnap Cam-Server feed” |
| intitle:”Live View / – AXIS 206M” | intitle:”Live View / – AXIS 206W” | intitle:”Live View / – AXIS 210” | inurl:indexFrame.shtml "Axis Video Server" | inurl:”MultiCameraFrame?Mode=Motion” | intitle:start inurl:cgistart | intitle:”WJ-NT104 Main Page” | intext:”MOBOTIX M1” intext:”Open Menu” |
| intext:”MOBOTIX M10” intext:”Open Menu” | intext:”MOBOTIX D10” intext:”Open Menu” | intitle:snc-z20 inurl:home/ | intitle:snc-cs3 inurl:home/ | intitle:snc-rz30 inurl:home/ | intitle:”sony network camera snc-p1” | intitle:”sony network camera snc-m1” | site:.viewnetcam.com -www.viewnetcam.com |
| intitle:”Toshiba Network Camera” user login | intitle:”netcam live image” | intitle:”i-Catcher Console – Web Monitor” | inurl:"axis-cgi/mjpg" | cgi-bin/video.jpg?size=2 | intitle:axis camera | inurl:"ViewerFrame?Mode=Motion" | inurl:"MultiCameraFrame?Mode=" |
| inurl:"video.cgi=" | inurl:"video.cgi?showlength=1" | "view/view.shtml" | "video.cgi?resolution=" | inurl:axiscam.net "AXIS" | inurl:axiscam.net "Live view" | inurl:mjpg/video.cgi | intitle:toshiba inurl:user_single_view.htm |
| "CgiStart?page=Single" | inurl:dyndns.org inurl:index.shtml | inurl:dyndns.org Axis|Mobotix | intitle:"Linksys Web Camera" "ver" | "Kamerainformationen anzeigen" | inurl:image?cachebust= | inintitle:"supervisioncam protocol" | title:flexwatch intext:"Copyright by Seyeon TECH Co" |
| "Powered by webcamXP" | -inurl:htm -inurl:html inurl:ViewerFrame | -inurl:htm -inurl:html inurl:webcam.php | camera linksys inurl:main.cgi | allintitle:Brains Corp. camera | intitle:"WJ-NT104 Main" | intitle:"WV-NP244" | inurl:home/homeJ.html |
| inurl:main/flashLogin.html | inurl:next_file=main_fs.htm | inurl:/login.ml | "Webthru User Login" | "Please enter username and password to log in to system" | inurl:Ctl/index.htm?Cus | Configuration "Pop-up Live Image" | inurl:Remote/index.php3 |
| intitle:Live Video | netw_tcp.shtml | "indexFrame.shtml?newstyle=Quad" | "/showcam.php?camid" | "live view" | intitle:"i-Catcher Console - Web Monitor" | "V.Networks [Motion Picture(Java" | inurl:/app/idxas.html |
| inurl:CgiStart?page=Single&Mode=Motion&Language=0 | | | | | | | |

9. 
| Google            | Запрос                                                                                           |
|-------------------|--------------------------------------------------------------------------------------------------|
| Google Videos     | `(intitle:"index of" (avi \| mkv \| mov \| wmv \| flv \| mpeg \| 3gp \| webm \| mp4))`           |
| Google Photos     | `(intitle:"index of" (jpg \| jpeg \| png \| gif \| bmp \| svg \| tiff \| webp))`                 |
| Google Audio      | `(intitle:"index of" (mp3 \| wav \| wma \| ogg \| flac \| aac \| m4a))`                          |
| Google Text       | `(intitle:"index of" (txt \| doc \| docx \| pdf \| odt \| rtf \| tex))`                          |
| Google Torrents   | `(intitle:"index of" (torrent))`                                                                 |
| Google Scripts    | `(intitle:"index of" (py \| js \| sh \| php \| rb \| pl \| java \| cs))`                         |

## Parameters Used

### File Extensions

|File Extension|Description|
|:----|:----|
|.xml|XML file format|
|.json|JSON (JavaScript Object Notation) file format|
|.properties|Properties file format used for configuration settings|
|.sql|SQL (Structured Query Language) file format used for database queries|
|.txt|Plain text file format|
|.log|Log file format used for recording events or activities|
|.tmp|Temporary file format|
|.backup|Backup file format|
|.bak|Backup file format|
|.enc|Encrypted file format|
|.yml|YAML (YAML Ain't Markup Language) file format used for configuration settings|
|.yaml|YAML (YAML Ain't Markup Language) file format used for configuration settings|
|.toml|TOML (Tom's Obvious, Minimal Language) file format used for configuration settings|
|.ini|INI (Initialization) file format used for configuration settings|
|.config|Configuration file format|
|.conf|Configuration file format|
|.cfg|Configuration file format|
|.env|Environment file format|
|.envrc|Environment file format specific to the Direnv tool|
|.prod|Production file format|
|.secret|Secret file format|
|.private|Private file format|
|.key|Key file format|


### Keynames

|Keynames|Description|
|:----|:----|
|access_key|Variable name to store the key used for accessing a resource or service|
|secret_key|Variable name to store the key used for authentication or encryption|
|access_token|Variable name to store the token used for accessing an API or resource|
|api_key|Variable name to store the key used for accessing an API or service|
|apikey|Shortened version of "api_key"|
|api_secret|Variable name to store the secret key used for API authentication|
|apiSecret|An alternate of "api_secret"|
|app_secret|Variable name to store the secret key used for application authentication|
|application_key|Variable name to store the key used for identifying an application|
|app_key|Variable name to store the key used for identifying an application|
|appkey|Shortened version of "app_key"|
|auth_token|Variable name to store the token used for authentication or authorization|
|authsecret|Variable name to store the secret key used for authentication or authorization|


## Other Useful Tools: 
- Telegram bot dumper - https://github.com/soxoj/telegram-bot-dumper
- Online IDE Search: https://redhuntlabs.com/online-ide-search/
- Keyhacks on GitHub: https://github.com/streaak/keyhacks
- Google Hacking Database: https://www.exploit-db.com/google-hacking-database

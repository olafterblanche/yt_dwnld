# yt_dwnld

## Description

Bash script to download youtube video as video or mp3 directly from terminal

## Instalation

At first you need to install youtube_dl

```
sudo apt-get install youtube-dl
```

Than download my script

```
wget https://raw.githubusercontent.com/OdkoPP/yt_dwnld/master/yt_dwnld -p ~ -O yt_dwnld
```

And finally make it executable
```
chmod +x yt_dwnld
```

## Usage


##### Help
```
./yt_dwnld -h
```

##### Download youtube URL as Video
```
./yt_dwnld -f video <URL>
```
By default Video will be saved to  **/home/<User_name>/Videos/Youtube_downloads**

##### Download youtube URL as MP3
```
./yt_dwnld -f mp3 <URL>
```
By default Video will be saved to  **/home/<User_name>/Music/Youtube_downloads**


## Examples

##### Download Video
```
./yt_dwnld -f video https://www.youtube.com/watch?v=uPy5igZJnVw
```

##### Download MP3
```
./yt_dwnld -f mp3 https://www.youtube.com/watch?v=uPy5igZJnVw
```

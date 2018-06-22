Make high-quality gifs in one easy step

I basically stole this script from [blog.pkh.me](http://blog.pkh.me/p/21-high-quality-gif-with-ffmpeg.html#usage) but I tweaked it to make it a lil more user friendly and configurable.

![You're welcome!](https://media.giphy.com/media/GqD83RQdaysWk/giphy.gif)

Usage
=====

```sh
gif [-f fps] [-w width] [-h height] <source video> <gif to make>
```

FPS defaults to 25 because it's a nice round number and 30 seems too high.
If you don't set a width or a height then it'll be the same as the source video.
If you set one but not the other the aspect ratio will be preserved.
If you set both then you'll get a gif of the dimensions you asked for.

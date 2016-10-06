# PomPom

View it here: [https://raggleton.github.io/PomPom](https://raggleton.github.io/PomPom)

A basic attempt as a Pomodoro timer, since none of the web ones seem to do it right without a gazzilion bells and whistles.

## requires

If you're offline, then the bootstrap (and therefore possibly jQuery) libraries will be needed.

To use sounds whilst developing, you should note that by default browsers block local files.
To get around this, just make a local httpserver in the `PomPom` dir:

```
python -m SimpleHTTPServer
```

Then just go to `http://localhost:8000/` in your browser.
Note that it doesn't seem to like local versions of bootstrap library, so working offline is a pain...

Sounds taken from <http://soundbible.com/royalty-free-sounds-1.html>, specifically <http://soundbible.com/2142-FogHorn-Barge.html> and <http://soundbible.com/2148-Chinese-Gong.html>.
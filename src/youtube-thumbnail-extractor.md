## YouTube thumbnail images extracter

2025-09-07
Coded with ChatGPT-5

I want you to write a YouTube thumbnail extractor. The base conditions are:

- The program is contained in an HTML page.
- No external dependencies: all css and javascript must be contained inside the html page.

Initially, the pages shows a text filed where the user can paste the url of a youtube video. After pressing a "Get Thumbnails" button, the program extracts the video id from the url and adds the following images to the page:

Default thumbnail image:

```
https://img.youtube.com/vi/<insert-youtube-video-id-here>/default.jpg
```

High quality thumbnail image:

```
https://img.youtube.com/vi/<insert-youtube-video-id-here>/hqdefault.jpg
```

Medium Quality thumbnail image:

```
https://img.youtube.com/vi/<insert-youtube-video-id-here>/mqdefault.jpg
```

Maximum resolution:

```
https://img.youtube.com/vi/<insert-youtube-video-id-here>/maxresdefault.jpg
```

Four additional generated images:

```
https://img.youtube.com/vi/<insert-youtube-video-id-here>/0.jpg
https://img.youtube.com/vi/<insert-youtube-video-id-here>/1.jpg
https://img.youtube.com/vi/<insert-youtube-video-id-here>/2.jpg
https://img.youtube.com/vi/<insert-youtube-video-id-here>/3.jpg
```

Each image should have these attributes displayed on the page:

- Image Size, dpi
- Text describing the image (high resolution, standard, etc.)

There should be a button to clean the page and start fresh.

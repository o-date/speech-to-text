Please visit [https://www.alexkras.com/transcribing-audio-file-to-text-with-google-cloud-speech-api-and-python/](https://www.alexkras.com/transcribing-audio-file-to-text-with-google-cloud-speech-api-and-python/) for detailed walk-through.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/o-date/speech-to-text/master)

1. get json-api.txt as per the blog post, then upload
2. examine the video you want with youtube-dl -F url-to-video
3. get the smallest audio file by noting the number beside it, then youtube-dl -f the-number url-to-video
4. put it in the source folder
5. mkdir parts
6. proceed with splitting the video 
7. rm -r parts/.ipynb_checkpoints
8. python fast.py



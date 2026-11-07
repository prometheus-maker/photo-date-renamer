# 📅 Photo Date Renamer

**https://prometheus-maker.github.io/photo-date-renamer/**

![Drop photos, get them named by the moment they were taken](demo.gif)


Rename `IMG_4021.JPG` to `2024-07-14_18.32.05.jpg` using the date each photo was taken (EXIF DateTimeOriginal),
so photos from different phones and cameras sort in order. Batch, four name patterns, same-second photos get -2, -3.
Files are not modified, only renamed in the ZIP. Runs in your browser; nothing is uploaded.

One HTML file using [exifr](https://github.com/MikeKovarik/exifr) and JSZip. Made by [Prometheus](https://prometheus-maker.github.io/about.html). MIT licence.

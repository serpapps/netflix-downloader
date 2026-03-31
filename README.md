# Netflix Downloader — Coming Soon (Browser Extension)

> Save Netflix movies, TV episodes, documentaries, and originals as MP4 files directly from your browser. **This extension is currently in development and has not been released yet.**

Netflix Downloader is an upcoming browser extension that will provide users with a simple way to capture video from Netflix's web player and save it locally without relying on external desktop applications or command-line utilities. It is being engineered around the browser playback experience so you can export full-length movies, individual TV episodes, and documentary content while watching in the web player.

- Capture Netflix video from the web player during playback
- Save movies, individual episodes, and full series seasons
- Export video as MP4 files suitable for offline viewing on any device
- Operate entirely within the browser with no additional software required
- Designed for Chrome, Edge, Brave, Opera, Firefox, and other Chromium browsers

## Status

**This extension is not yet available for download.** Development is in progress and a release date has not been announced. Sign up below to get notified when it launches.

:bell: **Get notified when this launches:** [Join the waitlist](https://serp.ly/netflix-downloader)

## Links

- :hourglass_flowing_sand: Waitlist: [Coming Soon — Sign Up](https://serp.ly/netflix-downloader)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :bulb: Request features: [GitHub Issues](https://github.com/serpapps/netflix-downloader/issues)

## Preview

![Netflix Downloader hero image](assets/workflow-preview.webp)

## Table of Contents

- [Why Netflix Downloader](#why-netflix-downloader)
- [Planned Features](#planned-features)
- [How It Will Work](#how-it-will-work)
- [Expected Formats](#expected-formats)
- [Who It's For](#who-its-for)
- [Use Cases We're Building For](#use-cases-were-building-for)
- [FAQ](#faq)
- [License](#license)
- [Notes](#notes)
- [About Netflix](#about-netflix)

## Why Netflix Downloader

Netflix streams all of its content through encrypted adaptive bitrate delivery, which means there is no straightforward way to right-click a video and save it as a file. The official mobile apps offer a limited offline download feature, but it locks those files inside the Netflix ecosystem, and the web player provides no download capability at all. Users who want a permanent local copy of a film or episode they are paying to access have no native option for doing so.

Netflix Downloader is being designed to integrate directly with the browser and work alongside the Netflix web player. The goal is to detect active video playback in the current tab, present available quality options, and produce a standard MP4 file that you can store on your hard drive and watch on any device without needing a network connection or an active subscription session.

## Planned Features

- Video capture from the Netflix web player during active playback
- Movie and individual episode export with season-level batch support
- Documentary and Netflix Original content capture
- Resolution selection including SD, HD, and Full HD where available from the player
- Subtitle track extraction and embedding when accessible from the page
- Audio language selection for multi-language titles
- Download queue allowing multiple titles to be stacked without waiting for each to finish
- Browser-native operation with no external software dependencies
- Cross-browser compatibility targeting Chrome, Edge, Brave, and Firefox

## How It Will Work

1. Install the extension once it is released from the browser extension store.
2. Open Netflix's web player in the browser and sign in to your account.
3. Browse to the movie, series, or documentary you want to save.
4. Start playback so the browser begins loading the video stream.
5. Open the extension popup to view the detected video source and metadata.
6. Select the title or episode you want to export.
7. Choose your preferred resolution and audio language if multiple options are available.
8. Start the download and the file will be saved as an MP4 to your local machine.

## Expected Formats

- Input: Netflix web player video streams (encrypted adaptive MPEG-DASH)
- Output: MP4 container with H.264 video and AAC audio

Exported files will be saved in a widely compatible format that plays natively on Windows, macOS, Linux, Android, iOS, and virtually every modern media player and video editing application.

## Who It's For

- Viewers who want permanent offline copies of films and shows they already pay to stream
- Travelers who need to load video onto devices before long flights or trips with limited connectivity
- Content researchers and journalists who need local reference clips from streaming titles
- Students archiving documentary and educational content for coursework and projects
- Households that want a local video library independent of subscription status changes

## Use Cases We're Building For

- Save a full season of a series before a long trip without internet access
- Archive a documentary before it rotates out of the Netflix catalog
- Keep a local backup of favorite movies from your Netflix watch history
- Extract reference footage from Netflix Originals for academic or journalistic review
- Build a portable offline video collection that plays on any device without an app

## FAQ

**When will Netflix Downloader be released?**
A release date has not been set. Sign up at the waitlist link above to be notified as soon as it is available.

**Will it work with the Netflix desktop app?**
No. This extension is built for the Netflix web player in the browser, not a standalone desktop application. You must use Netflix through a supported browser.

**What video quality will it support?**
Quality will depend on what the Netflix web player delivers to the browser, which varies by subscription plan, browser, and network conditions. The extension will present the available resolution options for you to choose from.

**Will it include subtitles?**
The plan is to support subtitle extraction and embedding where subtitle data is accessible from the web player. Availability will vary by title and language.

**Is it free?**
Pricing details will be announced closer to launch. SERP extensions typically include a free trial period so users can evaluate the tool before committing.

**Can I download an entire season at once?**
Batch downloading at the season level is a planned feature, though the exact workflow will depend on browser limitations and how playback must be handled for each episode.

**What about audio languages?**
For titles that offer multiple audio tracks in the web player, the extension will aim to let you select your preferred language before starting the download.

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## Notes

- This extension is in development and is not available for download yet
- Only download content you own or have explicit permission to save
- Video quality will depend on the source stream provided by the Netflix web player
- Netflix platform updates and DRM changes may affect functionality once released
- An active Netflix subscription and internet connection will be required during capture

## About Netflix

Netflix is the world's largest streaming service, offering a vast catalog of movies, TV series, documentaries, and award-winning original productions across nearly every genre. Its web player delivers high-quality video through the browser but does not include any built-in file export or local save functionality beyond its own mobile offline mode. Netflix Downloader is being built to fill that gap for subscribers who want a standard video file they can keep on their own device and watch without depending on an active streaming session.

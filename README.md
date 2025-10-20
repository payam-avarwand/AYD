# AYD (Avarwand YouTube Downloader)

A professional, Python-based **graphical YouTube downloader** for Windows, designed to easily download videos, playlists, and audio from YouTube with high performance and reliability.  
The application provides full **GUI control**, **automatic dependency installation**, **subtitle handling**, and **audio trimming**, all wrapped in a beautiful, compact interface.

---

## Main Features

- 🎞️ **Video & Audio Downloads**: Supports YouTube videos, audio-only extraction, and playlists.  
- ⚙️ **Quality Control**: Choose from 2160p, 1080p, 720p, or best-available for video; up to 320kbps for audio.  
- 🎧 **Audio Trim**: Optionally cut audio start and end time (hh:mm:ss) for MP3/WAV files.  
- 📂 **Flexible Output Formats**:  
  - **Video/Playlist**: MP4, MKV, WEBM  
  - **Audio Only**: MP3, WAV  
- 🗂️ **Subtitle Support**: Detects subtitle languages automatically and allows downloading with the video.  
- 🍪 **Cookies File Support**: Works with `.txt` or `.sqlite` YouTube cookies for authenticated downloads.  
- 🧩 **Dependency Auto-Installer**: Automatically installs **yt-dlp**, **psutil**, and **Pillow** if missing.  
- 🧠 **Smart Check Video Button**: Previews available qualities and subtitles before download.  
- 🧰 **FFmpeg Auto-Setup**: Downloads and configures FFmpeg if not present in the system.  
- 🪟 **Responsive GUI**: Built with Tkinter; supports progress bar, stop button, collapsible log, and real-time status.  
- 🔒 **Error Handling**: Detects and recovers from common download and network errors.  
- 🖼️ **Custom Look**: Modern GUI with dark red header, themed buttons, and built-in base64 icons.  

---

## System Requirements

- **Operating System**: Windows 10 or later (recommended); Linux compatible with minor adjustments  
- **Python Version**: 3.9 or later  
- **Dependencies**:
  - `yt-dlp`
  - `psutil`
  - `Pillow`
  - `tkinter` (built-in)

All dependencies will be **auto-installed** by AYD on first run.

---

## Usage

1. **Run the Application**  
   - Execute `AYD.py` or its `.exe` version.  
   - The main GUI window will open automatically.

2. **Select Mode**  
   - Choose **Video**, **Audio Only**, or **Playlist** mode.  

3. **Paste YouTube URL**  
   - Copy your video or playlist URL and paste it in the URL field.

4. **Choose Quality & Format**  
   - AYD automatically lists available qualities and formats.

5. **Download Location**  
   - Select your output folder (defaults to Desktop).

6. **Optional Settings**  
   - Add cookies file for login-based videos.  
   - Enable subtitles and choose language.  
   - Define audio trimming (start/end).

7. **Start Download**  
   - Click **Start** and monitor progress through the live status bar and log window.

8. **Stop Download**  
   - Click **Stop** to terminate ongoing downloads and remove incomplete files.

---

## Logging and Configuration

- All actions and messages are displayed in the **collapsible Log Window**.  
- Log entries can be **saved or cleared** directly from the GUI.  
- Temporary files are automatically cleaned after completion.

---

## Common Issues

- ❌ **Dependency Errors**: If auto-installation fails, install packages manually via pip.  
- ⚠️ **FFmpeg Missing**: AYD will auto-install FFmpeg to `C:\ffmpeg\bin`.  
- 🔑 **Cookies Authentication**: Use a valid `cookies.txt` or `cookies.sqlite` file.  
- ⏱️ **Slow Download**: Check your network connection or use a cookies file for age-restricted content.

---

## Technical Details

- **Programming Language**: Python 3  
- **Framework**: Tkinter (GUI)  
- **Downloader Engine**: yt-dlp  
- **Audio/Video Processing**: FFmpeg  
- **Automation Tools**: psutil, urllib, zipfile, regex  
- **License Type**: Freeware (Avarwand License)

---

## Contributing

This software is distributed as **freeware** by **Avarwand**.  
Suggestions, bug reports, and feature requests are welcome via email or GitHub issues.

---

## License

This software is released as freeware under the following terms:

**END USER LICENSE AGREEMENT (EULA)**  

This software, **AYD**, is provided by **Avarwand**, free of charge for personal and commercial use.  

By installing or using this software, you agree to:
- Use the software in compliance with the EULA  
- Not reverse engineer, decompile, or modify the software  
- Not redistribute or claim ownership of the software  
- Accept the software "as is" without warranties  

*For full EULA terms, see the LICENSE file in this repository.*

---

**Developed by Payam Avarwand**  
**Initial Release: October 2025**  
**Last Updated: October 18, 2025**

## Contact

**Payam Avarwand**  
Email: payam_avar@yahoo.com  

© 2025 Avarwand. All rights reserved.

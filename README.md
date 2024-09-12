# MelodyBot

A simple Discord bot to play MP3 files in voice channels. The bot can join voice channels, play, stop, and loop music, as well as change its online status.

(You can find the files in releases.)

# **WINDOWS ONLY**

## Features

- **Play Music**: Upload an MP3 file and use the `!play` command to play it in a voice channel.
- **Stop Music**: Use the `!stop` command to stop the currently playing music.
- **Loop Music**: Use the `!loop` command to loop the currently playing music.
- **Change Status**: Set the bot to online or offline with `!online` and `!offline` commands.
- **Disconnect**: Disconnect from the voice channel with the `!disconnect` command.

## Requirements

- Python 3.8 or higher
- `discord.py` library
- FFmpeg installed on your system

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/LolobrndVR/MelodyBot.git
   cd MelodyBot



## Installing FFmpeg

To ensure that FFmpeg is installed correctly on your system, follow these steps:

1. **Create the FFmpeg Directory**

   - On your C: drive, create a folder named `ffmpeg`.

2. **Add FFmpeg Files**

   - Open the `ffmpeg` folder you just created.
   - Copy or move the `bin` directory from your FFmpeg download into this folder.

3. **Install FFmpeg Using Windows PowerShell**

   - Open the Windows search bar and type `PowerShell`.
   - Press Enter to open PowerShell.
   - In the PowerShell window, type the following command and press Enter:

     ```bash
     winget install ffmpeg
     ```

   - Follow the on-screen instructions to complete the installation.

4. **Verify Installation**

   - Once installed, you can verify FFmpeg installation by opening a new PowerShell window and typing:

     ```bash
     ffmpeg -version
     ```

   - This command should display the installed version of FFmpeg.

Congratulations! You have successfully installed FFmpeg on your computer.
(I DO NOT OWN THE FFmpeg INSTALATION ! check the license)

## Installing Discord.py

```bash
pip install discord.py
```

## Running the program

```bash
python MelodyBot.py
```

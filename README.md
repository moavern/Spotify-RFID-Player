<p align="center"><img src="./recordplayerimage.png" width="800"></p>

## Modern Day Record Player

This homemade record player allows you to place an album cover ontop of the box, and it will automatically start playing the desired album. 

To do this, the record player used Radio-frequency identification (RFID), the same technology in your credit card when you tap to pay, and in access cards you scan to enter restricted buildings. This technology usually involves RFID chips such as in your credit card, and an RFID scanner such as a debit machine that can read the values of the card when it is tapped and perform an action accordingly.

In this project, the RFID scanner module is mounted inside the wooden box, and the vinyls all have an RFID sticker that can be tapped on the box to switch the album. Inside the box, the RFID scanner is wired to a Raspberry Pi, which is running a python program that switches the song based on the value it reads from the RFID scanner. Depending on the RFID sticker value, the corresponding album is played through the Spotify API.  

I wrote a detailed blog post on my website here:
ENTER WEBSITE


## Bill of Materials


- RFID RC522 Module with Soldered on Header Pins
    <a href="https://amzn.to/3BVej0s" target="__blank">🇺🇸 USA</a>
- RFID Stickers (13.56MHz)
    <a href="https://amzn.to/3hokkJv" target="__blank">🇺🇸 USA</a>
- Raspberry Pi 4 
    <a href="https://amzn.to/3hpanvm" target="__blank">🇺🇸 USA</a>
- Raspberry Pi 4 Power Supply
    <a href="https://amzn.to/3IsTo7v" target="__blank">🇺🇸 USA</a>
- Female to Female Dupont Jumper Wires
    <a href="https://amzn.to/3pnxWJw" target="__blank">🇺🇸 USA</a>
- Speakers



Blog Table of Contents
> 📌 Bill of Materials
>
> 📌 RFID Scanning
> - Wiring the RFID Scanner to the Rapsberry Pi
> - Setting up the Raspberry Pi
> - Using Python to Read RFID Sticker Values
>
> 📌 Spotify Integration
> - Making the Raspberry Pi a Spotify Connect Device
> - Spotify API Setup
> - Using Python to Control Spotify
>
> 📌 Combining the Spotify API and RFID Reader
> - Code to control Spotify API using RFID Values
> - Executing the Script on Startup of the Raspberry Pi
>
> 📌 Finishing Touches

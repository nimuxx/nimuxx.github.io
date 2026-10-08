---
layout: default
title: Humongous Collection
---

<h1 align="center" style="font-size: 56px !important;">Humongous Collection</h1>
<h2 align="center" style="font-size: 32px !important;">A modern, no-install, disc-based collection of<br>Humongous Entertainment games, powered by ScummVM.</h2>

<div style="max-width: 800px; margin: 30px auto -30px;">
  <table style="width: 100%; border-collapse: collapse; border: none;">
    <tr style="border: none;">
      <td style="width: 100%; border: none; padding: 0 0 0 0;" colspan=2>
        <img src="disc_full_demo.png" style="width: 75%; display: block; margin: 0 auto" alt="Demo images of the game discs." />
      </td>
    </tr>
    <tr style="border: none;">
      <td style="width: 50%; border: none; padding: 0 0 0 0;">
        <img src="bd-rom_case_cover.png" style="width: 100%; display: block;" alt="Demo images of the BD-ROM Edition cover." />
      </td>
      <td style="width: 50%; border: none; padding: 20px 0 0 0;">
        <img src="bd-rom_case_inside.png" style="width: 100%; display: block;" alt="Demo image of the BD-ROM Edition insert." />
      </td>
    </tr>
  </table>
</div>

---

This is a fan-made physical game disc release containing every Humongous Entertainment game that's compatible with ScummVM.

# Features
- It's portable; There is no need to install anything.
  - The game engine, game files, icon database, and configuration file are all loaded from the disc on the fly.
  - Saves, screenshots, and logs are stored on the local hard drive in the default locations for the installed version of ScummVM.
    - Save path: `%APPDATA%\ScummVM\Saved Games`
    - Screenshot path: `%USERPROFILE%\Pictures\ScummVM Screenshots`
    - Log path: `%APPDATA%\ScummVM\Logs\logfile.log`
- It has exceptional modern Windows compatibility.
  - Tested and working on Windows Vista, 7, 8, 10, and 11.
  - Fully supports both 32-bit (x86) and 64-bit (x64) versions of Windows.
  - Contains Autorun functionality with a disc icon and a custom launcher script. This lets you simply right-click your disc drive and run the launcher using the `Install or run program from your media` option.
- Thoughtfully crafted configuration and icon database files have been tailored to make the user experience as easy as possible; A kid should be able to figure it out without instructions. 
- It comes with fully custom physical release art, designed for a keep case (DVD case). This includes disc labels, wrap-around cover art, and an internal insert card.
- There are two (2) versions of the release based on your needs.
  - The first version is split between three single-layer DVDs. DVD drives are more common in PCs, but this version requires a keep case that supports 3 discs via an added middle flap.
  - The second version fits everything on one single-layer Blu-ray. Blu-ray drives aren't as common in PCs, but this version can be stored in a standard 1-disc keep case.

---

# Downloads
- 3 DVD-ROM Set
  - <a href="https://drive.google.com/drive/folders/1CL1tkFbq0vU7fBG9TMU9z9LP7TtWmeK5">[GOOGLE DRIVE]</a>
  - <a href="magnet:?xt=urn:btih:1ae420f5e488ee0a7ac0db0427f28daf399e419f&dn=Humongous%20Collection%20%283%20DVD-ROM%20Set%29&xl=13210636438&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce">[MAGNET LINK]</a>
- BD-ROM Edition
  - <a href="https://drive.google.com/drive/folders/1I4RSSHDaRd4DgBy6jJA_bBxS3XNiK9U-">[GOOGLE DRIVE]</a>
  - <a href="magnet:?xt=urn:btih:fba2cbdb5665c36dda9d7fee0f3e048d0ca6742d&dn=Humongous%20Collection%20%28BD-ROM%20Edition%29&xl=12735166811&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.demonii.com%3A1337%2Fannounce&tr=udp%3A%2F%2Fopen.stealth.si%3A80%2Fannounce">[MAGNET LINK]</a>
- Archival Backup
  - <a href="https://archive.org/details/humongous-collection">[INTERNET ARCHIVE]</a>

---

# How to Make a Physical Release
1. Download either the `3 DVD-ROM Set` or the `BD-ROM Edition` from the links above.
    - You only need the `.iso` and `.png` files to make a physical release. You can skip downloading all the `.md5` and `.par2` files if you aren't concerned about corrupted downloads.
    - Optionally, if you want some way to verify and repair corrupted downloads, then you can download the `.md5` and `.par2` files as well.
        
        - The `.par2` files only provide 1% redundancy to keep the total package small while still providing a little bit of error tolerance. If you're trying to make an archival backup that can survive heavy data rot, download the `Archival Backup` instead, which has 100% redundancy `.par2` files for HDD backup, in addition to archival `.iso` files with 100% - 200% redundancy built in using [`dvdisaster`](https://github.com/speed47/dvdisaster).
        
2. Burn the `.iso` file(s) to the disc(s). Use `4x` - `8x` speed for best results.
    - At this point, if you don't care about having pretty labels or box art for the disc(s), you can just label them with a marker and skip the rest of this section.
3. Print and cut the artwork in the `Print` folders out at 300 DPI. <span style="color: var(--highlight-color)"><u>Do not scale the artwork when printing.</u></span> There is an example of what each item should look like after being cut to its final size in the `Preview` folders.
    - The disc label(s) should be printed on pre-cut adhesive CD labels. You will either need to learn how to align the artwork to the CD label paper or pay a local print shop to do it for you.
    - The cover art should be printed on gloss or semi-gloss paper. When cutting it out, try to trim about `3 mm` of the artwork off on every side. The artwork was designed to be cut out this way.
    - The internal insert should be printed on either semi-gloss or matte paper that's thicker than printer paper. Again, it was designed to be cut out by trimming `3 mm` of printed artwork off on each side.
4. Apply the labels to the disc(s), put the front cover and internal insert into the keep case, and you're done! Congratulations, you have now created a physical game release!

---

# How to Play
1. Insert the disc into your disc drive and wait for it to show up in Windows.
2. On older versions of Windows, you will get an Autorun popup prompting you to run the startup script. On newer versions, you will need to right-click the disc drive in Windows Explorer and select `Install or run program from your media`. If all else fails, you can manually run the script by double-clicking on `Run.bat`.
3. Wait for a minute or so while the data is read from the disc. You may see a command window that lingers for a moment, then disappears; this means that the game engine is loading in the background. <u>Do not run the launcher script more than once, or multiple launcher windows will open.</u>
4. When the ScummVM launcher finally shows up, double-click the game you wish to play. The game files will be loaded from the disc, and your game will start.
5. You can exit your game at any time, and you will return to the ScummVM launcher. Clicking the exit button a second time on the launcher screen will quit the launcher entirely.
6. When you are done playing, exit the ScummVM launcher completely, then eject the disc. <u>Ejecting the disc while the engine is still running can result in strange bugs and possible save game corruption.</u>

---

# Included Games
The DVD-ROM version of this collection has the games split up between 3 DVD discs:

## Disc 1 of 3
- Big Thinkers
  - Big Thinkers 1st Grade <span style="color: var(--highlight-color)">(1997)</span>
  - Big Thinkers Kindergarten <span style="color: var(--highlight-color)">(1997)</span>
- Blue's Clues
  - Blue's 123 Time Activities <span style="color: var(--highlight-color)">(1999)</span>
  - Blue's ABC Time Activities <span style="color: var(--highlight-color)">(1998)</span>
  - Blue's Clues: Blue's Art Time Activities <span style="color: var(--highlight-color)">(2000)</span>
  - Blue's Birthday Adventure <span style="color: var(--highlight-color)">(1998)</span>
  - Blue's Reading Time Activities <span style="color: var(--highlight-color)">(2000)</span>
  - Blue's Treasure Hunt <span style="color: var(--highlight-color)">(1999)</span>
- Fatty Bear
  - Fatty Bear's Birthday Surprise <span style="color: var(--highlight-color)">(1993)</span>
  - Fatty Bear's Fun Pack <span style="color: var(--highlight-color)">(1993)</span>
  - Putt-Putt and Fatty Bear's Activity Pack <span style="color: var(--highlight-color)">(1994)</span>
- Junior Field Trips
  - Let's Explore the Airport with Buzzy <span style="color: var(--highlight-color)">(1995)</span>
  - Let's Explore the Farm with Buzzy <span style="color: var(--highlight-color)">(1994)</span>
  - Let's Explore the Jungle with Buzzy <span style="color: var(--highlight-color)">(1995)</span>

## Disc 2 of 3
- Freddi Fish
  - Freddi Fish 1: The Case of the Missing Kelp Seeds <span style="color: var(--highlight-color)">(1994)</span>
  - Freddi Fish 2: The Case of the Haunted Schoolhouse <span style="color: var(--highlight-color)">(1995)</span>
  - Freddi Fish 3: The Case of the Stolen Conch Shell <span style="color: var(--highlight-color)">(1998)</span>
  - Freddi Fish 4: The Case of the Hogfish Rustlers of Briny Gulch <span style="color: var(--highlight-color)">(1999)</span>
  - Freddi Fish 5: The Case of the Creature of Coral Cove <span style="color: var(--highlight-color)">(2001)</span>
  - Freddi Fish and Luther's Maze Madness <span style="color: var(--highlight-color)">(1997)</span>
  - Freddi Fish and Luther's Water Worries <span style="color: var(--highlight-color)">(1997)</span>
  - Freddi Fish's One-Stop Fun Shop <span style="color: var(--highlight-color)">(2000)</span>
- Pajama Sam
  - Pajama Sam 1: No Need to Hide When It's Dark Outside <span style="color: var(--highlight-color)">(1996)</span>
  - Pajama Sam 2: Thunder and Lightning Aren't so Frightening <span style="color: var(--highlight-color)">(1998)</span>
  - Pajama Sam 3: You Are What You Eat from Your Head to Your Feet <span style="color: var(--highlight-color)">(2000)</span>
  - Pajama Sam's Lost & Found <span style="color: var(--highlight-color)">(1998)</span>
  - Pajama Sam's One-Stop Fun Shop <span style="color: var(--highlight-color)">(2000)</span>
  - Pajama Sam's Sock Works <span style="color: var(--highlight-color)">(1997)</span>
  - Pajama Sam: Games to Play On Any Day <span style="color: var(--highlight-color)">(2001)</span>
- Putt-Putt
  - Putt-Putt and Fatty Bear's Activity Pack <span style="color: var(--highlight-color)">(1994)</span>
  - Putt-Putt and Pep's Balloon-o-Rama <span style="color: var(--highlight-color)">(1996)</span>
  - Putt-Putt and Pep's Dog on a Stick <span style="color: var(--highlight-color)">(1996)</span>
  - Putt-Putt Enters the Race <span style="color: var(--highlight-color)">(1999)</span>
  - Putt-Putt Goes to the Moon <span style="color: var(--highlight-color)">(1993)</span>
  - Putt-Putt Joins the Circus <span style="color: var(--highlight-color)">(2000)</span>
  - Putt-Putt Joins the Parade <span style="color: var(--highlight-color)">(1992)</span>
  - Putt-Putt Saves the Zoo <span style="color: var(--highlight-color)">(1995)</span>
  - Putt-Putt Travels Through Time <span style="color: var(--highlight-color)">(1997)</span>
  - Putt-Putt's Fun Pack <span style="color: var(--highlight-color)">(1993)</span>
  - Putt-Putt's One-Stop Fun Shop <span style="color: var(--highlight-color)">(2000)</span>
- SPY Fox
  - SPY Fox 1: Dry Cereal <span style="color: var(--highlight-color)">(1997)</span>
  - SPY Fox 2: Some Assembly Required <span style="color: var(--highlight-color)">(1999)</span>
  - SPY Fox 3: Operation Ozone <span style="color: var(--highlight-color)">(2001)</span>
  - SPY Fox in Cheese Chase <span style="color: var(--highlight-color)">(1998)</span>
  - SPY Fox in Hold the Mustard <span style="color: var(--highlight-color)">(1999)</span>

## Disc 3 of 3
- Backyard Sports
  - Backyard Baseball <span style="color: var(--highlight-color)">(1997)</span>
  - Backyard Baseball 2001 <span style="color: var(--highlight-color)">(2000)</span>
  - Backyard Baseball 2003 <span style="color: var(--highlight-color)">(2002)</span>
  - Backyard Basketball <span style="color: var(--highlight-color)">(2001)</span>
  - Backyard Football <span style="color: var(--highlight-color)">(1999)</span>
  - Backyard Football 2002 <span style="color: var(--highlight-color)">(2001)</span>
  - Backyard Soccer <span style="color: var(--highlight-color)">(1998)</span>
  - Backyard Soccer 2004 <span style="color: var(--highlight-color)">(2003)</span>
  - Backyard Soccer MLS Edition <span style="color: var(--highlight-color)">(2000)</span>
- Moonbase Commander
  - Moonbase Commander <span style="color: var(--highlight-color)">(2002)</span>

---

The BD-ROM version contains all the games on a single Blu-ray disc:

## Complete Disc
- Backyard Sports
  - Backyard Baseball <span style="color: var(--highlight-color)">(1997)</span>
  - Backyard Baseball 2001 <span style="color: var(--highlight-color)">(2000)</span>
  - Backyard Baseball 2003 <span style="color: var(--highlight-color)">(2002)</span>
  - Backyard Basketball <span style="color: var(--highlight-color)">(2001)</span>
  - Backyard Football <span style="color: var(--highlight-color)">(1999)</span>
  - Backyard Football 2002 <span style="color: var(--highlight-color)">(2001)</span>
  - Backyard Soccer <span style="color: var(--highlight-color)">(1998)</span>
  - Backyard Soccer 2004 <span style="color: var(--highlight-color)">(2003)</span>
  - Backyard Soccer MLS Edition <span style="color: var(--highlight-color)">(2000)</span>
- Big Thinker
  - Big Thinkers 1st Grade <span style="color: var(--highlight-color)">(1997)</span>
  - Big Thinkers Kindergarten <span style="color: var(--highlight-color)">(1997)</span>
- Blue's Clues
  - Blue's 123 Time Activities <span style="color: var(--highlight-color)">(1999)</span>
  - Blue's ABC Time Activities <span style="color: var(--highlight-color)">(1998)</span>
  - Blue's Clues: Blue's Art Time Activities <span style="color: var(--highlight-color)">(2000)</span>
  - Blue's Birthday Adventure <span style="color: var(--highlight-color)">(1998)</span>
  - Blue's Reading Time Activities <span style="color: var(--highlight-color)">(2000)</span>
  - Blue's Treasure Hunt <span style="color: var(--highlight-color)">(1999)</span>
- Fatty Bear
  - Fatty Bear's Birthday Surprise <span style="color: var(--highlight-color)">(1993)</span>
  - Fatty Bear's Fun Pack <span style="color: var(--highlight-color)">(1993)</span>
  - Putt-Putt and Fatty Bear's Activity Pack <span style="color: var(--highlight-color)">(1994)</span>
- Freddi Fish
  - Freddi Fish 1: The Case of the Missing Kelp Seeds <span style="color: var(--highlight-color)">(1994)</span>
  - Freddi Fish 2: The Case of the Haunted Schoolhouse <span style="color: var(--highlight-color)">(1995)</span>
  - Freddi Fish 3: The Case of the Stolen Conch Shell <span style="color: var(--highlight-color)">(1998)</span>
  - Freddi Fish 4: The Case of the Hogfish Rustlers of Briny Gulch <span style="color: var(--highlight-color)">(1999)</span>
  - Freddi Fish 5: The Case of the Creature of Coral Cove <span style="color: var(--highlight-color)">(2001)</span>
  - Freddi Fish and Luther's Maze Madness <span style="color: var(--highlight-color)">(1997)</span>
  - Freddi Fish and Luther's Water Worries <span style="color: var(--highlight-color)">(1997)</span>
  - Freddi Fish's One-Stop Fun Shop <span style="color: var(--highlight-color)">(2000)</span>
- Junior Field Trips
  - Let's Explore the Airport with Buzzy <span style="color: var(--highlight-color)">(1995)</span>
  - Let's Explore the Farm with Buzzy <span style="color: var(--highlight-color)">(1994)</span>
  - Let's Explore the Jungle with Buzzy <span style="color: var(--highlight-color)">(1995)</span>
- Moonbase Commander
  - Moonbase Commander <span style="color: var(--highlight-color)">(2002)</span>
- Pajama Sam
  - Pajama Sam 1: No Need to Hide When It's Dark Outside <span style="color: var(--highlight-color)">(1996)</span>
  - Pajama Sam 2: Thunder and Lightning Aren't so Frightening <span style="color: var(--highlight-color)">(1998)</span>
  - Pajama Sam 3: You Are What You Eat from Your Head to Your Feet <span style="color: var(--highlight-color)">(2000)</span>
  - Pajama Sam's Lost & Found <span style="color: var(--highlight-color)">(1998)</span>
  - Pajama Sam's One-Stop Fun Shop <span style="color: var(--highlight-color)">(2000)</span>
  - Pajama Sam's Sock Works <span style="color: var(--highlight-color)">(1997)</span>
  - Pajama Sam: Games to Play On Any Day <span style="color: var(--highlight-color)">(2001)</span>
- Putt-Putt
  - Putt-Putt and Pep's Balloon-o-Rama <span style="color: var(--highlight-color)">(1996)</span>
  - Putt-Putt and Pep's Dog on a Stick <span style="color: var(--highlight-color)">(1996)</span>
  - Putt-Putt Enters the Race <span style="color: var(--highlight-color)">(1999)</span>
  - Putt-Putt Goes to the Moon <span style="color: var(--highlight-color)">(1993)</span>
  - Putt-Putt Joins the Circus <span style="color: var(--highlight-color)">(2000)</span>
  - Putt-Putt Joins the Parade <span style="color: var(--highlight-color)">(1992)</span>
  - Putt-Putt Saves the Zoo <span style="color: var(--highlight-color)">(1995)</span>
  - Putt-Putt Travels Through Time <span style="color: var(--highlight-color)">(1997)</span>
  - Putt-Putt's Fun Pack <span style="color: var(--highlight-color)">(1993)</span>
  - Putt-Putt's One-Stop Fun Shop <span style="color: var(--highlight-color)">(2000)</span>
- SPY Fox
  - SPY Fox 1: Dry Cereal <span style="color: var(--highlight-color)">(1997)</span>
  - SPY Fox 2: Some Assembly Required <span style="color: var(--highlight-color)">(1999)</span>
  - SPY Fox 3: Operation Ozone <span style="color: var(--highlight-color)">(2001)</span>
  - SPY Fox in Cheese Chase <span style="color: var(--highlight-color)">(1998)</span>
  - SPY Fox in Hold the Mustard <span style="color: var(--highlight-color)">(1999)</span>

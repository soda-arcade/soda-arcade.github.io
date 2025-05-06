---
layout: flarecast
title: Home

data:
    panels:
        - title: "What is FlareCast?"
          content: "FlareCast (also known as Smash Soda) lets you play local multiplayer games with friends using just one PC. Everyone connects their own controllers to your computer, making it perfect for game nights and parties. No extra consoles needed - just your PC and controllers!"
        - title: "How to Use"
          content: "1. Start by going to this link and downloading the Community edition of Visual Studio 2022:

          https://visualstudio.microsoft.com/downloads/

          2. Launch the downloaded installer, and in the window that pops up, scroll down until you find \"Desktop development with C++\" and enable it. Then click \"Install\".

          3. When prompted to sign in, click \"Skip this for now\" and set your colour scheme preference for the editor.

          4. Select \"Clone a repository\" and then in the \"Repository location\" field enter:

          https://github.com/mickeyuk/smash-soda
          Select your preference for where you want the files downloaded to in the \"Path\" field. Then click \"Clone\".

          5. In the bottom right corner of the new window, select \"Git Changes\", which will show the Git Changes panel. Whenever updates are made to Smash Soda, you will be able to update your files automatically by clicking the down arrow icon in the top right of the Git Changes window (will show \"Pull\" when you put your mouse over it).

          6. In the menu bar at the top, select \"View\", then \"Git Repository\". This will show you a timeline of all the changes made to the repository that you can review yourself so that you know exactly what it is you're building and what has been added/removed.

          7. When you are ready to build, below the top menu bar you should see a dropdown menu with \"Debug\" selected. Change this to \"Release\", and the dropdown next to it, set the architecture for your PC (x64 is 64 bit, x86 is 32 bit). If you are unsure, press the Windows key and the Pause Break key at the same time. In the window that pops up, it will tell you under \"System Type\".

          8. Press CTRL + B or click the green play button. Soda should now start building (might take a while!)

          If there are errors, join the Discord server here and post in this thread:
          ⁠Mickey's Hub

          9. The built Smash Soda will go inside the folder you save the cloned repository too, inside the \"x64\" folder, and then inside the \"Release\" folder.

          10. Ensure you have the latest version of ViGEmbus (this is what Soda uses for the controller stuff!).

          https://github.com/nefarius/ViGEmBus/releases

          11. If you want to be able to use the new overlay system, then inside the root directory (where the SmashSoda.exe file is), create a new folder called \"overlay\".

          12. Download the standalone Smash Soda overlay application from here (the Smash-Soda-Overlay-x64-v1.0.zip file):

          https://github.com/MickeyUK/smash-soda-overlay/releases

          13. You're all set! Be sure to check the Discord server for Soda support and discussion!

          Soda Arcade Discord Server"
        - title: "Origins"
          content: "FlareCast is a modification of ParsecSoda, a tool originally created by FlavioFS to enhance Parsec Arcade hosting. This version builds upon improvements made by user v6000. This is an experimental version of Parsec Soda...expect bugs! Help development by reporting issues and/or joining the Discord!"
---
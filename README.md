<h1 align = "center">
    <a href="https://github.com/skobnx/ShadowverseEvolveCockatrice/archive/refs/heads/main.zip"><img src = "https://imgur.com/eWuWoF2.jpg" width="1000">
</h1>

<p align="center">
  <a href="#Shadowverse-Evolve-Cockatrice">Shadowverse Evolve Cockatrice</a> •
  <a href="#Download">Download</a> •
  <a href="#Updating">Updating</a> •
  <a href="#Optional-Steps">Optional Steps</a> •
  <a href="#How-to-Use">How to Use</a> •
  <a href="#Helpful-Tips">Helpful Tips</a>
</p>

---

## Shadowverse Evolve Cockatrice

Welcome to the guide on how to import a custom set XML file to Cockatrice. This guide will help you seamlessly integrate the Shadowverse Evolve game into your Cockatrice program. Please follow the step-by-step instructions below.

**Disclaimer:** Please note that we do not own any rights to the Shadowverse franchise. This package is a compilation of publicly available information and is intended solely for personal enjoyment without any profit motive.

## Download
**Prerequisite:** Make sure you have [Cockatrice](https://cockatrice.github.io/) installed on your computer (Windows, Mac, Linux, etc). If not, download and install Cockatrice from the provided link.

1. [Download](https://github.com/skobnx/ShadowverseEvolveCockatrice/archive/refs/heads/main.zip) the latest ShadowverseEvolveTCG.xml file by clicking the download link or the Forte banner.  

2. Unzip the zipped folder and look for the "ShadowverseEvolveTCG.xml" file in the list of files. Remember where you store the xml file for the next few steps. 

3. Open the Cockatrice program. If a prompt appears indicating that it will run Oracle, allow it to do so.

4. In Cockatrice, navigate to "Card Database" and select "Manage Sets". From the dropdown menu, choose "Open custom sets folder".

5. Locate the "Shadowverse Evolve.xml" file you downloaded from the GitHub page. Move this file into the folder that opened in the previous step.

6. Close Cockatrice completely, and then reopen it. You will see a prompt indicating that new sets are being added. It will ask if you want to enable them. Click "Yes" to enable the Shadowverse Evolve sets.

Congratulations! Shadowverse Evolve is now fully integrated into your Cockatrice program. Enjoy playing the game to the fullest!

## Updating

1. When a new set of cards is out, redownload the xml file.

2. Repeat steps 1-6 to replace the old xml file in the "custom sets folder". 

## Optional Steps
These steps are completely optional, but doing so improve your overall experience with the program. 

<h3> Dark Mode </h3>

Cockatrice's default is white mode. Of course, no one wants to blind their eyes while playing Shadowverse. This [dark mode](https://github.com/mingomongo/DarkMingo-Theme-for-Cockatrice) extension will change Cockatrice to be dark mode. 

## How to Use
<h3> Finding Shadowverse Evolve Cards </h3>

When you open Cockatrice, there are will be Shadowverse Evolve and Magic: the Gathering cards into the lists of cards. No worries, we have that secured. On filters sections, click on the dropdown and select "Format". Type **Shadowverse** or **SV** to filter for only Shadowverse Evolve cards.

<img src = "https://cdn.discordapp.com/attachments/480908885956362242/1126713575440916601/card-search.png">

<h3> Making a Deck </h3>

- Cockatrice has two decks, the main deck and side deck. Thus, we will use the main deck for our main deck, and use the the side deck for our evolve deck. 
- To add cards to your deck, search for the card you want to add, and double click on it. It will automatically add the card to the main deck. To move the card to your evolve deck, double click on the card from the main deck.
- It is recommended to add one Land card in the evolve deck to help keep track of used and unused mana. Of course, it is not required and completely optional. 

Your deck should look like this: 
<img src = "https://cdn.discordapp.com/attachments/480908885956362242/1126711058233561108/forestcraft-deck.png">

<h3> Setting Up </h3>

- To start playing games on Cockatrice, you will need to an account. 
    - If you need to register an account, click on "Cockatrice" and "Register to server". Enter a player name, password, email, and click OK. Afterward, accept the verification email to verify your account. 
    - If you already have an account, click on "Cockatrice" and "Connect" to login. 
-  Once logged in, click on the "Server" tab and select "Other Games" to find other players to play Shadowverse Evolve. 
    - Because Cockatrice is an MTG-oriented program for online play, you won't be able to find Shadowverse Evolve players with open rooms at all unless you are either 1. extremely lucky, 2. my plugin became famous, or most likely 3. you asked a buddy to play.  #3 is how you'll get matches 99.9% of the time.  
    - Quickest way to ask for games is to ask for games in the [Shadowverse Evolve](https://discord.gg/shadowverse-evolve-tcg-community-928746294384677004) server or other social media platforms.
- Once you enter the room, click "Load deck" on the top left corner to select the deck you want to use and "Ready to start".

<h3> Playing the Game </h3>

- Right-click "Sideboard" to open your Evolve deck and put down your leader.
- Right-click "Roll the die" to see who goes first. 
- Draw four cards by double clicking the deck. You can perform mulligans by highlighting every card, right clicking "Bottom to the deck in random order", and drawing four new cards. 
<img src = "https://cdn.discordapp.com/attachments/480908885956362242/1126729079429800067/Mulligan.gif"> 
- Now this is where the Land cards become helpful to keep track of play points. As you start your turn, right-click "Clone" on the Land card to make a copy. Tap the Land cards to spend play points. If you play Magic: the Gathering or Force of Will, this may seem similar as it is how they keep track of their play points. 
- On the top left, there is an "Untap" button which lets you untap all the cards on the field. 

## Helpful Tips
- Yep, Cockatrice has built-in keyboard shortcuts you can press to heighten your play experience with the program.  Common ones include (for Windows users): 
- Ctrl+D: Draw 1 card from deck
- Ctrl+S: Shuffle deck
- Ctrl+F3: View sideboard (for accessing your LRIG Deck)
- Ctrl+E: Draw any number of cards from deck
- Ctrl+W: Look at any number of cards on the top of your deck

There's more than this, but knowing these should be enough to let your play speed and comfiness go way up.  If you want to know more shortcuts, right clicking on various areas and objects will show a menu of actions you can do, some showing their shortcut and others not having any.

- Playing manually does give many perks however, especially when learning the game.  Developing good card movement habits, memorizing turn/phase order, and needing to socially interact with your opponent are but a few advantages that manual sims offer that automated ones do not nearly as easily.

## Questions & Answers
We will have the cards updated as quick as we can. Keep in mind that we are inputting the cards in the xml file manually as there is no API for Shadowverse Evolve card database. We continuously maintain and update this plugin, completely free of charge and for the benefit of the community.  If/when an update isn't coming as quickly as you want it, please be patient, life happens sometimes. 

<img src = "https://cdn.discordapp.com/attachments/480908885956362242/1126354128101199913/mid_game.png" width="1000">

<img src = "https://cdn.discordapp.com/attachments/480908885956362242/1126353629889171476/late_game.png" width="1000">
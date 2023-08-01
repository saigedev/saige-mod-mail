# DevSaige's Semi-Advanced Discord Modmail Bot Feature
A package made with JavaScript to help you create an amazing, customizable and functional Discord mod mail bot!

# Customize Setup 
```
const saigemodmail = require('saige-mod-mail');

client.on("ready", () => {
saigemodmail.ModMail(client, {
  guildID: "ID",
  categoryID: "ID",
  staffRole: "ID",
  embedColor: "HEX",
  anonymousReply: false/true,
  closedTitle: "Your Mod Mail Has Been Closed",
  closedMessage: "A Staff Member Has Deleted You Mod Mail!",
  staffOpenedTitle: "User Opened Mod Mail",
  staffOpenedMessage: "The User Opened A Mod Mail And Is Now Wait For A Reply!",
  userOpenedTitle: "Mod Mail Created",
  userOpenedMessage: "You Created A Mod Mail Ticket!",
  wrongEmoji: "EMOJI",
  rightEmoji: "EMOJI" 
})
});
```

- 👋 Hi, I’m @sfqfqn
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
sfqfqn/sfqfqn is a ✨ special ✨ repoconst express = require("express")
const app = express();
var listener = app.listen(process.env.PORT || 2000, function () {
  console.log('Your app is listening on port ' + listener.address().port);
});
app.listen(() => console.log("I'm Ready To Work..! 24H"));
app.get('/', (req, res) => {
  res.send(`
  <body>
  <center><h1>Bot 24H ON!</h1></center
  </body>`)
});

const { Client } = require('discord.js-selfbot-v13');
const client = new Client(); 

client.on('ready', async () => {
  console.log(`${client.user.username} is ready!`);
})

const { joinVoiceChannel } = require('@discordjs/voice');
client.on('ready', () => {

    setInterval( async () => {
    client.channels.fetch(process.env.channel) 
     .then((channel) => { 
      const VoiceConnection = joinVoiceChannel({
       channelId: channel.id, 
       guildId: channel.guild.id, 
       adapterCreator: channel.guild.voiceAdapterCreator 
       });
    }).catch((error) => { return; });
    }, 1000)
}); 

client.login(process.env.token);sitory because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

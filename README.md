

## Technologies Used

- NodeJS
- Cheerio
- DialogFlow
- FB Messenger for Developers

### How to run

1.  Clone this repo.  
2.  Setup a proxy server with ngrok and set the port number to be the same as the one defined in Node. It is 3000 by default.
3. 	Run the ngrok server.
4. 	Setup the respective app on FB developers account using the Forwarding URL obtained in previous step and the token you entered in 'controllers/verification.js'.
5.	Insert your API Keys for FB Developers and DialogFlow into the file 'helpers/processMessage.js'.
6. 	Apply the required integrations on DialogFlow.
7.  Run index.js. If all is well with your bot, you should get replies from the bot in Messenger for some simple questions.

## What can it do?
RecipeBot can do a variety of things related to recipes. Some of them are-
-	Lookup recipes for you and provide them to you stepwise.
-	List dishes you can make with the ingredients you have.
-	Lookup for alternate ingredients that you may use in case some ingredients are not available.
-	Alert dishes according to a particular festival or occasion.


## Project description:
A platform for people to sell their video games to others. We use a video game database API (RAWG) to make it easy for people to list their games, autofilling the rest of the information once they type the title. Once a seller lists a game, buyers will be able to find it by browsing or searching available games. Once they find a game they like, they are able to buy it, removing it from the available games. In short, it allows the user to Create, Read, Update, and Delete listings from a database.


## Description:
Sellers are able to: 
- Create an account and log in with their credentials.
- Add video games they want to sell as listings. Once the title of the game is entered, the rest of the information about the game is filled from the RAWG API.
- Add / edit the prices and details of their listings from their personal listings dashboard.
- Delete their video game listings.


Buyers are able to:
- Search and filter listings by 3 fields: genre, name, and price.
- View all information about the game listing, including value given by seller.
- "Purchase" the game, which removes it from the listings table and adds it to a table of sold games.

## How to run
1. To run the application, first clone it.
2. Then, run `npm install` from the root folder to install all necessary dependencies.
3. Run `node index.js` to start the application.

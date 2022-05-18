# Food Ordering App Backend
This repository contains backend part of [Food Ordering App](https://github.com/DomSas/Food-Ordering-App) to communicate with Stripe for online payments. Tutorial is available on this Medium blog.

### Files

`index.js` - contains code for Express server  
`Procfile` - description for Heroku deployment to determine how to start the app

### How to use

1. Fork or download the repository.
2. Insert secret key obtained from Stripe website on line 4: https://github.com/monaca-samples/food-ordering-app-backend/blob/3fa589543127d0cbf573e3af794600f92bf303ba/index.js#L3-L5
3. Start the server locally with `npm run start`, or deploy the app on Heroku to be publicly available.

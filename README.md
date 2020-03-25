# SpotifyShuffler - OATH Bridge

This is a microservice that runs an express server that serves as a login portal to Spotify. It assumes that you have a frontend running on localhost:3000 or a FRONTEND_URI environment variable. The final access token from Spotify is contained in the query string access_token. This token allows the frontend to make requests for the user's info using the token.

### A true shuffle button for Spotify Users

#### There's no current way in Spotify to SHUFFLE

I don't mean shuffling a playlist, or a library, I mean shuffling everything you've ever PUT in a playlist, a library, which can be artists, albums, or songs. This is a simple way to fire up your application and control it via a big old shuffle button.

### Featuring

-  Spotify web api oauth

# Infinite Dungeon Crawler

Infinite Dungeon Crawler is an evolution of the text-adventure game utilizing OpenAI's API to generate dynamic and unending stories around the users actions.

## Installation

Clone this repository to your local machine and install all dependencies.

## Usage

To use this application you will need either a local postgres database or a hosted one you can connect to.

If you have a local database, its name will have to match the name in your package.json. Or you can go to server/db/db and manually change the connection there.

Otherwise, you will need to create a .env file and have "DATABASE_URL" as your key.

In order to get the responses back from OpenAI, you will also need an API key from OpenAI placed in your .env with the key as "OPENAI_API_KEY"

```
# npm run seed
seeds your database

# npm run start
starts your server (for testing your routes)

# npm run start:dev
starts your server and builds client-side files. go to localhost:8080
```

Other commands can be found in the package.json but this should be enough to get you up and running!

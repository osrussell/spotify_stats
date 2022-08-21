# Spotify Stats Website
## Author: Olivia Russell

This is the source code for a spotify web app using the Spotipy package displayed with github pages.

# Outline

Below we have an outline of the flow of the repository:

[to be added]

## Setup

I used a virtual environment to manage any modules and run the notebooks. To begin using modules and notebooks in this repo, run the following commands:

```
$ python3 -m venv venv # Creates a virtual environment
$ source venv/bin/activate # Activates virtual environment
$ python3 -m pip install --upgrade pip
$ python3 -m pip install -r requirements.txt # Download requirements
```

You must also create a ```.env``` file and populate it with your CID and SECRET from your own spotify developer project. You can get these from making a developer account at [Spotify for Developers](https://developer.spotify.com) and starting a project. 

Your .env file should look like:

```
CID="ecc2c6f460af4005bd9695812de2b96c"
SECRET="35a4b2384ba74549bd44899cf27ea4d9" 
```

## Further Info

For more information about the Spotipy package, the documentation can be explored [here](https://spotipy.readthedocs.io/en/2.19.0/).

For more information about the Spotify API, the documentation can be explored [here](https://developer.spotify.com/discover/).

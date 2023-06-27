# Pokemon assets downloader V2

## To update the assets

- Change the [HOME] Pokémon Renders mega files to update the database.
- Open the python file and run `python3 pokemon.py`
- This will update the pokedexdata.json according to the new **pokedb.net** pokemon database, and also it will update the Images/normal.json and Images/shiny.json accroding to the newly uploaded images in [HOME] Pokémon Renders
- Pokedex json has reverse pairing too i.e. `pokemonName : pokedexNumber` and `pokedexNumber : pokemonName`

## Features

- One can search by Pokemon name or 4 digit pokedex number
- After typing four characters of the Pokemon, search suggestions will show up.
- Different forms of the Pokemon are categorised into the same name. For example - typing Charizard will list Charizard, X, Y, gigantamax etc forms and its shinies.
- Clicking on the images is the simplest way to download it.
- Search suggestions are clickable and show-up your pokemon.

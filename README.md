# PokéAlert ![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg)


Live Pokémon, Pokéstops and gym visualization map based on [AHAAAAAAA's project](https://github.com/AHAAAAAAA/PokemonGo-Map/wiki).

Features from the original version:
* Shows Pokemon, Pokéstops, and gyms with a clean GUI.
* Notifications
* Lure information
* Multithreaded mode
* Filters
* Independent worker threads (many can be used simulatenously to quickly generate a livemap of a huge geographical area)
* Localization (en, fr, pt_br, de, ru, zh_cn, zh_hk)
* DB storage (sqlite or mysql) of all found pokemon
* Incredibly fast, efficient searching algorithm (compared to everything else available)

Added features for this fork:
* Cry sounds from the original Game Boy games for appearing Pokémon.
* Sound notification for newly activated lures in PokéStops.

To do:
* Add browser notifications for new active lures, and make the sound optional for the notification.
* Add a few more lure notification sound options.
* Change cries to be a sound option for specific Pokémon notifications.
* Give the option to activate notifications for _any_ Pokémon except the ones on the exclude list.

## How to setup

For instructions on how to setup and run the tool, please refer to the original project's [wiki](https://github.com/AHAAAAAAA/PokemonGo-Map/wiki), or the [video guide](https://www.youtube.com/watch?v=RJKAulPCkRI).


## Warnings

Using this software is against the ToS of the game. You can get banned, use this tool at your own risk.


## Credits

Building off [tejado's python pgoapi](https://github.com/tejado/pgoapi), [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s API, [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps). Current version relies primarily on the pgoapi and Google Maps JS API.

Sounds from [zhanxj's post on Reddit](https://www.reddit.com/r/pokemon/comments/1s16ht/651_pokemon_cries_in_wav_and_493_cries_in_mp3_saw/).

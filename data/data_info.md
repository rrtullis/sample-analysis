
This file contains a high-level overview of the dataset used for this analysis. Information regarding the meaning of each column was limited - most of the descriptions listed below were based on manual inspection of the data and domain knowledge.

Source:  
Martin Bustos Roman (2022). *Steam Games Dataset*. Kaggle.  
[https://www.kaggle.com/ds/2109585](https://www.kaggle.com/ds/2109585)

| Feature | Description | Type | Included |
|---------|-------------|------|-----------|
| name    | Game name| str | N |
| release_date| Release date | str | Y |
| required_age | Age required to play | int | Y |
| price | Price in USD | float | Y |
| dlc_count | Number of DLCs | int | Y|
| detailed_description | Detailed text description of game | str | N |
| about_the_game | Text description of the game | str | N |
| short_description | Short text description of the game | str | N |
| reviews | Text reviews of the game | str | N |
| header_image | URL of the store image | str | N |
| website | URL of the game's website | str | N |
| support_url | URL of the game's support website | str | N |
| support_email | URL of the game's support email | str | N |
| windows | Whether the game supports Windows | bool | N |
| mac | Whether the game supports Mac | bool | Y |
| linux | Whether the game supports Linux | bool | Y |
| metacritic_score | The game's Metacritic score | int | Target |
| metacritic_url | URL of the game's Metacritic review | str | N |
| acheivements | The number of achievements the game has | int | Y |
| recomendations | The number of "Recommended" reviews the game has recieved |int | Y |
| notes | Text notes and content warnings for the game | str | N |
| supported_languages | List of languages the game has a translation for | list of str | Y |
| full_audio_languages | List of languages the game has full audio for | list of str | Y |
| packages | List of dictionaries of different bundles or editions of the game available for purchase | list of dict | N |
| developers | List of the developers of the game | list of str | N |
| publishers | List of the publishers of the game | list of str | N |
| categories | List of categories the game is a member of | list of str | Y |
| genres | List of genres the game fits | list of str | Y |
| screenshots | List of URLs of images on the game's store page | list of str | N |
| movies | Unknown; all rows contain only the empty list [] | list | N |
| user_score | SteamSpy user score of the game, out of 100 | int | N |
| score_rank | SteamSpy game rank, based on user_score | int | N |
| positive | Number of positive SteamSpy user votes |int | Y |
| negative | Number of negative SteamSpy user votes | int | Y |
| estimated_owners |Interval estimate of the number of people who own the game on Steam |category | Y |
| average_playtime_forever | Average total playtime (hours) of game owners | int | Y |
| average_playtime_2weeks | Average playtime (hours) of game owners over the last 2 weeks | int | Y |
| median_playtime_forever | Median total playtime (hours) of game owners | int | Y |
| median_playtime_2weeks | Median playtime (hours) of game owners over the last 2 weeks | int | Y |
| discount | The current discount percentage of the game | int | N |
| peak_ccu | The highest recorded number of concurrent players | int | N |
| tags | List of tags users have applied to the game | list of str | Y |


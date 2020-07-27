# Watchlist

Watchlist is an Amazon Alexa Skill that recommends Netflix shows and movies to watch

## Project Details
Built with the Python 3.6 AWS SDK

Retrieving updated Netflix library availability from uNoGS via RapidAPI

Retrieving video metadata (genres, etc.) from IMDb via RapidAPI

Recommendation engine currently hardcoded into voice prompts

API data wrappers called from separate lambda

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

If you would like to contribute, create an 'apikey.py' file in the source folder and include your own RapidAPI key for it to call data correctly.  Be sure to add this file into your .gitignore before submitting a PR

## Contact
```python
name  : 'Rachel Sheikh'
email : 'sheikhrachel97@gmail.com'
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

## TODO
Fill out user prompts within recommendation lambda

Build API data wrapper lambda to filter requests

Create intents in Alexa Developer Console

# Twitter API Integration

This bot uses the Twitter API to post tweets. Below are the key endpoints and their use:

## Authentication
- OAuth 2.0 Bearer Token

## Endpoints
1. **POST /statuses/update.json**
   - Posts a new tweet.

Example Code:
```python
client.create_tweet(text="Your tweet here!")

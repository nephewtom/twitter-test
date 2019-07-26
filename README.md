# Instructions
Things I had to do to get this up & running:

- Install `gem` installing via `scoop install ruby`
- Run: `gem install twurl`
- Authorize:
```
$ twurl authorize --consumer-key <consumer-key> --consumer-secret <consumer-secret>
Go to https://api.twitter.com/oauth/authorize?oauth_consumer_key=<consumer-key>&oauth_nonce=xxxxx&oauth_signature=xxxxx&oauth_signature_method=HMAC-SHA1&oauth_timestamp=1564132474&oauth_token=xxxxx&oauth_version=1.0 and paste in the supplied PIN
7607594
Authorization successful
```
  Paste the PIN on the provided URL
  Note: xxxxx are values returned in that query.
  
- Use the API

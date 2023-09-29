# Manage_Twitter_API_with_Jmeter
This Repositoryused to test twitter API's with Jmeter

I have used OAuth 1.0a HMAC-sha1 mechanism,  to dvelop and validate twitter API.

Prearuisites

1. Register to Twitter developer portal
2. Create your project and Apps.
3. Generate your API keys and tokens for more details follow below link.

https://developer.twitter.com/en/docs/tutorials/step-by-step-guide-to-making-your-first-request-to-the-twitter-api-v2

You can refer further using POSTMAN API collections.
 https://www.postman.com/twitter/workspace/twitter-s-public-workspace/collection/9956214-784efcda-ed4c-4491-a4c0-a26470a67400?ctx=documentation.

 Once you have above we have to to look following document to focus how to build our script to meet twitter oauth1.0 a reuirement.

 1.Create a signature base string
 2. Create sigining base key using Consumer secret & OAuth token secret
 3. finally create Oauth signature key with above two values.
 4. pass authriozation values in header of your http request

 https://developer.twitter.com/en/docs/authentication/oauth-1-0a/creating-a-signature
 

 

 # Qualtrics API usage

This repo contains postman config for a part of Qualtrics API shared for hackathon. Also, there are some helpful resources which should help you to better understand and use this in your project

## Shared apis

We decided to share with you following APIs:
- [Surveys CRUD API](https://api.qualtrics.com/140945f8e06fd-surveys-crud-api)
    
- [Survey Responses](https://api.qualtrics.com/354c312da7cc7-survey-responses)
    
- [Qualtrics Survey API](https://api.qualtrics.com/60d24f6897737-qualtrics-survey-api)
    
- [Surveys Response Import/Export API](https://api.qualtrics.com/206a07d54ca31-surveys-response-import-export-api)

## Other helpful resources

[Building surveys](https://api.qualtrics.com/ZG9jOjg3NzY2Nw-building-surveys)

[Managing surveys](https://api.qualtrics.com/ZG9jOjg3NzY3Mw-managing-surveys)

[Getting Survey Responses Using New Export APIs](https://api.qualtrics.com/ZG9jOjg3NzY3MA-getting-survey-responses-via-the-new-export-ap-is)

[Survey API - Example Use Cases Walkthrough](https://api.qualtrics.com/ZG9jOjg3NzY4Mw-example-use-cases-walkthrough)

## How to set up postman client
1. Download [postman](https://www.postman.com/downloads/)
2. Download `Hackathon Kraków 2022 - Survey APIs.postman_collection.json` from this repo
3. Import the configuration using the `Import` button:
<img width="381" alt="image" src="https://user-images.githubusercontent.com/52859917/199741125-9b4e590f-9c2b-478a-b366-ab27f91c12ec.png">
4. Create a new environment, and inside of it use following variables (you will receive token at the start of the hackathon) (values are just an example, you would need to create your own survey and use its surveyId etc...):
<img width="1122" alt="image" src="https://user-images.githubusercontent.com/52859917/199741241-7c8902a6-0abb-4197-bd28-4d36c034ee14.png">
5. You should be able to send requests now!

## FAQ

Q: I've created a survey, can I see/fill it somehow?
A: Yes, it should be accessible at `https://krakowhackathon2022.g1-iad.qualtrics.com/jfe/form/{surveyId}`

Q: I see that there is an endpoint in shared APIs which is not present in postman, can I still use it?

A: Yes, We've only included a part of endpoints here, feel free to set them up by yourself and use them. You can submit an MR to this repo if you want to add a configuration :3


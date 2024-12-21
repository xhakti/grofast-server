1. generate already 5 different types of tweets and when clicked on refreshed instead of calling the gpt api again show the next tweet 
2. only call the api when he changes the prompt or edits the prompt 
3. make the ui look like a chat interface and use partners as their faces.

1. Create the authentication flow with supabase 
2. Connect and create account of the user with supabase for now 
3. Add zod validation for api authentication 

4. Create a system for referals and people with referal code can get 50% off  and for each 5 sucessfull referal you get one month of gro fast premium subscription free

Api 

1. 
Name: Generate Message
Endpoint: /generate-message
Method: POST
Input: persona and prompt 
Output: a tweet

2. 
Name: Generate replies
Endpoint: /generate-replies
Method: POST
Input: persona and prompt 
Output: a array of 4 replies 

3. 
Name: Save texts
Endpoint: /save-texts
Method: POST
Input: message
Output: msg






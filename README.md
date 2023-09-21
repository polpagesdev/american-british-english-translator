# American-British English Translator
RESTful API that translates American English to British English and vice versa.

The API can be accessed by sending a POST request to the following URL, with the text to be translated in the body of the request:
https://american-british-translator.freecodecamp.rocks/api/translate

The request body should be a JSON object with the following property:
{
  "text": "The text to be translated"
}

The response will be a JSON object with the following property:
{
  "translation": "The translated text"
}

The API is implemented using the Express framework and Node.js. The translation logic is based on a dictionary of American English and British English words and phrases.

You can see the live version of the code and running app in my Repl: https://replit.com/@polpages1999/american-british-english-translator?v=1

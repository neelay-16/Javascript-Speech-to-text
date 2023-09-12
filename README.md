# Javascript-Speech-to-text
Welcome to the Voice to Text Converter project! This simple web application allows you to convert spoken words into text using your device's microphone. It's a fun and practical tool that can be easily integrated into your web applications. Let's get started!

# Preview   

https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/8567f077-2ae1-420f-87df-3f2ffa84a525

# Features

1. Voice Recognition: The application uses the Web Speech API to recognize your voice and convert it into text.
2. Language Support: Currently, the application is set to recognize English (en-GB), but you can easily change the language by modifying the recognition.lang attribute in the code.
3. Easy Integration: You can integrate this feature into your own web applications by following the provided code example.


# Description

This is the beginning of an HTML document. It includes a <head> section where you specify the title of the web page, and a <body> section where the main content of the page will reside.

![image](https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/37a4787b-168c-42d0-bbc9-ae32bc920cac)


This is an title that serves as the main title of the web page, indicating that this page is for a "Voice to Text Converter."

![image](https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/eb2e826d-da23-4111-950d-301ea58fb86c)


This creates a <textarea> element with the id attribute set to "speechToText." It provides a text input area where the converted text from the voice input will be displayed. The rows and cols attributes determine the number of visible rows and columns in the textarea.

![image](https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/602ea06f-44ea-4063-8f7c-b335801c7a53)

This is a <button> element labeled "Voice to Text." When clicked, it triggers the voice() JavaScript function to start converting voice to text.

![image](https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/1233a767-dbe3-4ccb-bf0c-092f616611e8)


This <script> element contains JavaScript code that will be executed when the page loads or when specific events occur.

![image](https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/d6398517-7834-4867-b0a9-4c93e31f92f0)

The voice() function is defined to handle voice recognition and text conversion.
It creates a SpeechRecognition object using the webkitSpeechRecognition constructor if available or the standard SpeechRecognition constructor.
The recognition.lang property is set to "en-GB," specifying that the recognition should be in British English.
The recognition.onresult event handler is defined to handle the recognition results. When speech is recognized, it logs the event to the console and sets the value of the "speechToText" textarea to the recognized transcript.
Finally, the recognition.start() method is called to start listening for voice input when the button is clicked.

![image](https://github.com/neelay-16/Javascript-Speech-to-text/assets/135517502/77d12f0a-51f6-40f3-bfb7-a7c414b065e1)












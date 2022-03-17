# Customer_Feedback_Analysis
$ pip install pydub
$ pip install ffmpeg
$ pip install SpeechRecognition
$ pip install spacy
$ python -m spacy download en_core_web_sm

- To work with audio files we'll use pydub library of python. But pydub only works with .wav format of files, so we'll check if the data we have contains files in .wav format, if they're not we'll convert them using the helper function *convert_to_wav()*
- We then transcribe our audio files using the recognizer class of the SpeechRecognition library
- We can use spaCy to find named entities in our transcribed text. Named entities are real-world objects which have names, such as, cities, people, dates or times. 

Below is the reference link for this python script to understand the voice:
https://www.youtube.com/watch?v=K_WbsFrPUCk

Other References:
https://www.youtube.com/watch?v=sHeJgKBaiAI

---------------------------------------------------
Some useful commands are as follows:

1)	To upgrade python:
python -m pip install --upgrade --user pip

2) Install Speech Recognition using below command:
python -m pip install SpeechRecognition

----------------------------------------------------
Challenges Faced by Speech Recognition:
1) Style of Speaking(eg: American/French/German Accent/British English/American English)
2) Environment(eg: Isolated Room/ Echoing Environment)
3) Speaker Characteristics(Old person's voice vs a child's voice)
4) Task Specifiers(Some vocal utterances may not have the viable meaning)

----------------------------------------------------
Packages which can be used for Speech Recognition:
1) apiai
2) assemblyai
3) Google-cloud-speech
4) SpeechRecognition
5) PocketSphinx
6) Watson-developer-cloud
7) wit

--------------------------
Recognizer class basically has instances which are used to recognize speech. Each instance has seven methods 
to recognize speech from any audio source using various apis.
1) recognize_bing()
2) recognize_google()
3) recognize_google_cloud()
4) recognize_houndify()
5) recognize_ibm()
6) recognize_sphinx() -> for offline recognition
7) recognize_wit()



# voice-assistant

Basic Voice Assistant built using SpeechRecognition and gtts libraries that use Google API for recognising speech and responding with text to speech.

The Voice Assistant can be activated by a Key Word/ Wake Word/ Identifier.
The assistant identifier used in this program is 'Chip'
All commands should start with 'Hey Chip' to be recognized by the Assistant.

You can check the date, time, and weather using this Voice Assistant.
It can also be used to maintain a To Do List and to send emails.

To stop the Voice Assistant, say 'Hey Chip, stop'


## Example Commands

**For date and time:**

'Hey Chip, what's today's date?'
'Hey Chip, what's tomorrow's date?'
'Hey Chip, what is the time?'



**For temperature and weather:**

'Hey Chip, what is the weather today?'
'Hey Chip, what is the temperature?'



**For To Do List:**

'Hey Chip, list my tasks'
'Hey Chip, can you add a task?'
'Hey Chip, can you remove a task from the list?'



**For Sending a Mail:**

'Hey Chip, can you send an email for me?'



**For quitting/ stopping the application:**

'Hey Chip, stop running.'


Note:
Chip notes the keywords present in your commands to identify what action the user requires to be performed. 
For example, any of the below commands:
'Hey Chip, tell me the weather', 'Hey Chip, what's the weather', 'Hey Chip, do you know what the weather is today?'
and any other variations can be used to find out information about the weather.


## Before Running
1. Download all required libraries using pip (speechrecognition (yes, without the underscore), gtts, pyglet and pyaudio). The libraries not mentioned here usually come preinstalled with python. However, if that's not the case, go ahead and pip install them as well. 
2. Run on a local machine (not VM) to ensure access to microphone.
3. Ensure that microphone access is turned on for Python Executables.
4. Preferably use headphones and in an area with low background noise. Ensure you are unmuted and the system volume is moderate.
5. The Google API takes some time to process your audio. Be patient.
6. Create a free account on the ipinfo website and get a token for yourself to insert into the code at specified location.
7. Insert your gmail address and password into the code at the specified location.
8. Ensure that you change the settings for your google account from which you will be sending emails to allow access to 'less secure apps'. This can be done through the account settings.

# HQ Trivia Cheat on Google Colab
Cloud based HQ Trivia cheat on Google Colab. Bot created by Exaphis

# https://colab.research.google.com/drive/1U6SPcbOAE-nqEF_P0HSwsbJp5oYOzWoD

## Getting Started
Requires Python 3.6+
### Dependencies
#### Required
```
aiohttp
bs4
lomond
nltk
unidecode
```
#### Optional
```
aiodns
cchardet
```
### Installation
```
git clone https://github.com/Exaphis/HackQ-Trivia.git
cd HackQ-Trivia
pip install -r requirements.txt
```

If on Mac, run: 
```
/Applications/"Python 3.6"/"Install Certificates.command"
```

In Python 3, run:
```
import nltk
nltk.download("all")
```
Enter your bearer token in the conn_settings.txt file. This value can be found by sniffing the traffic on your phone. The bearer token should be one line, without the word Bearer.

### Usage
```
python3 hq_main.py
```

If ```RuntimeError: Connection settings invalid``` appears, then your bearer token is invalid.

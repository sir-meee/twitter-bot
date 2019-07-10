# Twitter-Bot Script

This is an application that automatically logs in, searches for a keyword/hashtag, pulls all tweets related and likes them every few seconds.  

### Prerequisites

You need to have installed python3.6 using pip, install selenium using pip, have mozilla firefox installed and mozilla gecko driver(download from mozilla github)or run the following in your terminal:

```
## Geckodriver
wget https://github.com/mozilla/geckodriver/releases/download/v0.23.0/geckodriver-v0.23.0-linux64.tar.gz
sudo sh -c 'tar -x geckodriver -zf geckodriver-v0.23.0-linux64.tar.gz -O > /usr/bin/geckodriver'
sudo chmod +x /usr/bin/geckodriver
rm geckodriver-v0.23.0-linux64.tar.gz

## Chromedriver
wget https://chromedriver.storage.googleapis.com/2.29/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
sudo chmod +x chromedriver
sudo mv chromedriver /usr/bin/
rm chromedriver_linux64.zip
```


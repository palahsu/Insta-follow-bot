# Insta-follow-bot

An instagram bot developed in Python with Selenium that helps you get more Instagram followers.
## Install
You’ll need to have:

 - [Python](https://www.python.org/downloads/)
 - [Selenium](https://pypi.org/project/selenium)
 - [Google Chrome](https://www.google.com/chrome/)
 - [Chromedriver](https://chromedriver.chromium.org/downloads)
 - [webdriver-manager](https://pypi.org/project/webdriver-manager)

Go check them out if you don't have them locally installed.

If you have correctly downloaded Chromedriver and install.

## Usage

Open **main.py** , you’ll have to change some lines.

1. Change your_username and your_password to your Instagram credentials.
```
#
username = 'your_username'
password = 'your_password'
```
2. Change this line with your custom tags.
```
#
tags = ['l4l','','','']
```
3. In order to keep your account safe and not locked out, you should be satisfied with less than 500 likes per day.
```python
#
while  like_cnt < 100:
	like()
```
4. Run
```
 instafollowbot.py
```

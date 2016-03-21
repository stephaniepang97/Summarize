# Summarize
Chrome extension summarizing articles using SMMRY API
Stephanie Pang

In this directory: 
	- manifest.json
	- popup.html
	- popup.js
	- popup.css
	- canterbury.regular-webfont.eot
	- canterbury.regular-webfont.svg
	- canterbury-regular-webfont.ttf
	- canterbury-regular-webfont.woff
	- canterbury-regular-webfont.woff2
	- images/
		- icon_19.png
		- icon_38.png
		- icon_128.png
	- README.pdf
	- README.txt (same as pdf but without pictures)

Description:
This Chrome extension places a clickable icon next to the browser's Omnibox. If the user is clicks on this icon, a popup window will appear where the user can select the number of sentences the summary will contain. Then the user can click on the Summarize button located in the same popup window and a summary (or an error message, if summary is not available) will appear. 

Steps for use:
	- Download Summarize.crx 
	- Open Google Chrome
	- Go to "chrome://extensions/" by typing it in the search bar
	- Drag and drop the downloaded Summarize.crx file onto the extensions page
	- Click "Add Extension" when the installation popup window appears

***NOTE***: 
Because I used the SMMRY API, which requires an API key that allows only 10 summary requests every 24 hours for free, the popup will display a "quota reached" message after 10 summaries. If you would like to use Summarize after the quota is reached, below is a list of free SMMRY API keys that I registered for that you may use. Just copy a key from the list below and replace it with the string found in line 103 of Summarize/popup.js, to the left of the comment that states /*API KEY*/.

Available SMMRY API keys to use for testing: 
	- 789A22476A
	- 7167C2FD51
	- C42AEF7580
	- EB0DA4D0FD
	- BBBB508331
	- 97408699AF
	- 5783A318EB
	- 85B3671999 <-- initial API key in code

See README.pdf for examples and screenshots of Summarize

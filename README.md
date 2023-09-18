# Swiss German language pack for ProcessWire
Swiss German (de_CH) language pack for [ProcessWire](http://processwire.com) which uses informal language ("Du").

We will try to stay up to date with the most recent stable version of ProcessWire.

Big thanks to [Jens Martsch](https://github.com/jmartsch) for the previous work and indirectly to Matthias Mees and Nico Knoll for their initial work.

## Installation
To install a language pack, you must have the ProcessWire Language Support module installed. This is included with ProcessWire, so all you have to do is click to Modules > Language > Language Support > install.

### Install as additional language
Once you have Language Support installed, you can install this language pack by going to Setup > Languages > Add New Language. Enter a title and name for the language and save.

Next, you can install the files for the language pack. If your system supports ZIP uploads, you can simply drag the ZIP file for the language pack into the files field. If your system doesn't support ZIP uploads, then you'll want to unzip the language pack and drag the JSON files (as a group, or individually) into the files field. Save.

Now you can test out the new language by editing our profile and selecting the new language.

Menu items are translated after you log out and log in again.

### Install and replace the default language
With this installation type your ProcessWire admin would also be translated to the new language.

Horst Nogajski wrote a [great tutorial with screenshots](https://processwire.com/talk/topic/23627-change-default-language-to-be-none-english-walk-trough/) how to replace the default language.

In short, it works like this (taken from Horst's writing):
1) enable languages support 

2) set title / label of the default language to your desired none english native language, (e.g. 'Deutsch' (German))

3) drop in the none english language pack (for admin backend) into the default language, (e.g. german langpack)

4) Now you are ready to start with a single language site of your choice.

5) If you want to use a multi-language site, you now can add as many additional languages you want. If one of them should be english, you add it, but do not need to apply a language pack.
    - add a new language to it and drop in a language pack for any none english language or simply don't drop in a language pack to get the english version (but not as the default one!)

For single language sites you only need to enable "ProcessWire Language Support", not Language Inputfields and Language Pagenames!

## Contribute to the language pack
This section is work in progress.

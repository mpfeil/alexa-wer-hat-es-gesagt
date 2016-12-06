# alexa-wer-hat-es-gesagt [![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg)](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg) [![Certification Status](https://img.shields.io/badge/Status-Live-orange.svg)](https://img.shields.io/badge/Status-Live-orange.svg) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://img.shields.io/badge/license-MIT-blue.svg)

> Wenn man keine Ahnung hat: Einfach mal Fresse halten! - Dieter Nuhr

Alexa testet dein Wissen rundum bekannte Zitate! 

## Entstehung
Diese Alexa Fähigkeit (Skill) ist im Rahmen des Alexa Skill Building Berlin Bootcamp entstanden. Dabei handelt es sich um die einfachste Art einer Alexa Fähigkeit. Diese Fähigkeit basiert auf dem [Alexa Trivia Skill](https://github.com/alexa/skill-sample-nodejs-trivia).

## Äußerungen (Utterances)
Mit den folgenden Aussagen, kannst du Wer hat es gesagt steuern:
```
die Antwort ist {Answer}
meine Antwort ist {Answer}
ist die Antwort {Answer}
{Answer} ist meine Antwort
{Answer}

Spiel starten
neues Spiel
starten
neues Spiel starten

weiß ich nicht
weiß nicht
überspringen
das weiß ich nicht
wer weiß
diese Frage weiß ich nicht
die weiß ich nicht
keine Ahnung
```
Die Äußerungen müssen in der Entwicklung spezifiziert werden. Die Äußerungen findest du unter `src/Utterances_de_DE.txt`.

Bevor du die Äußerungen sagst und Alexa dich mit einer Fussballweisheit bespaßt, musst du die Fähigkeit öffnen/aktivieren. Dies kannst du folgendermaßen machen:
```
Alexa, öffnen wer hat es gesagt
Alexa, starte wer hat es gesagt
```
Danach kannst du dann die oben genannten Äußerungen benutzen.

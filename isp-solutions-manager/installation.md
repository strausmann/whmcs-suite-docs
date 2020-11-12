# Installation

## Requirements

Der ISP Solutions Manager hat folgende Systemanforderungen:

* [iocube loader](https://www.ioncube.com/):
  * 10.4.0+
* PHP:
  * 7.2+
* PHP Extentions:
  * curl
  * json
* PHP Settings:
  * max\_execution\_time 300
  * memory\_limit min. 256MB
* [Composer](https://getcomposer.org/):
  * v2.0.6+

## Download

Der ISP Solutions Manager steht nach dem Kauf einer unserer WHMCS Addons im [Kundencenter ](https://kundencenter.isp-serverfarm.de/solutionsmanager.php)für Download zur Verfügung.

![](../.gitbook/assets/image.png)

Bei dem ersten Aufruf der Seite wird ein API Key generiert, der ab diesem Zeitpunkt ein Jahr lang gültig ist.  
Notieren Sie sich den Key, der wird für die spätere Installation des ISP Solutions Managers im WHMCS benötigt.

![](../.gitbook/assets/image%20%281%29.png)

## Installation

### Upload

Entpacken Sie die ispserverfarm-updater\_latest.zip und laden Sie den Inhalt direkt in das Root Verzeichnis von WHMCS hoch. Der Inhalt der ZIP enthält bereits die erforderliche Verzeichnisstruktur für die korrekte Platzierung im WHMCS

### Konfiguration

Nach dem Upload muss das Addon aktiviert und der API Token in das Feld "Solutions Manager Token" eingetragen werden.

![ISP Solutions Manager Setup](../.gitbook/assets/image%20%282%29.png)

Nach dem Speichern wird mithilfe des API Token die weitere Einrichtung des Solutions Manager vorgenommen. Über einen API Call zu unserem System der Username und Token für unsere Composer Repositories übermittelt. Der Token ermöglicht auch die Abfrage der gekauften Produkte.


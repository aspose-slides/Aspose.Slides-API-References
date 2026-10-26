---
title: DigitalSignature class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/digitalsignature/
---
## DigitalSignature Klasse

Digitale Signatur in einer signierten Datei.

Der DigitalSignature-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/de/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Zertifikat. |
| [`__init__(self, file_path, password)`](/slides/python-net/de/aspose.slides/digitalsignature/__init__/#str-str) | Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Pfad zur Zertifikatsdatei und dem Passwort. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`certificate`](/slides/python-net/de/aspose.slides/digitalsignature/certificate/) | Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde.<br/>            Nur lesbar **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/de/aspose.slides/digitalsignature/is_valid/) | Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert true.<br/>            Nur lesbar **bool**. |
| [`sign_time`](/slides/python-net/de/aspose.slides/digitalsignature/sign_time/) | Der Zeitpunkt, zu dem das Dokument signiert wurde.<br/>            Nur lesbar **System.DateTime**. |
| [`comments`](/slides/python-net/de/aspose.slides/digitalsignature/comments/) | Der Zweck der Signatur.<br/>            Lesen/Schreiben **str**. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)
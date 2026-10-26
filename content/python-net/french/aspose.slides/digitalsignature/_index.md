---
title: DigitalSignature class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/digitalsignature/
---
## DigitalSignature classe

Signature numérique dans le fichier signé.

Le type DigitalSignature expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/fr/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Creates a new DigitalSignature object with the specified certificate. |
| [`__init__(self, file_path, password)`](/slides/python-net/fr/aspose.slides/digitalsignature/__init__/#str-str) | Creates a new DigitalSignature object with the specified certificate file path and password. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`certificate`](/slides/python-net/fr/aspose.slides/digitalsignature/certificate/) | Objet certificat utilisé pour signer le document.<br/>            Lecture seule **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/fr/aspose.slides/digitalsignature/is_valid/) | Si cette signature numérique est valide et que le document n'a pas été altéré, cette valeur sera vraie.<br/>            Lecture seule **bool**. |
| [`sign_time`](/slides/python-net/fr/aspose.slides/digitalsignature/sign_time/) | Le moment où le document a été signé.<br/>            Lecture seule **System.DateTime**. |
| [`comments`](/slides/python-net/fr/aspose.slides/digitalsignature/comments/) | Le but de la signature.<br/>            Lecture/écriture **str**. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
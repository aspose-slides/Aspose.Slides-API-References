---
title: DigitalSignature class
second_title: Aspose.Slides dla Pythona poprzez .NET odwołanie API
description: 
type: docs
url: /pl/aspose.slides/digitalsignature/
---
## DigitalSignature klasa

Podpis cyfrowy w podpisanym pliku.

Typ DigitalSignature udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/pl/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Tworzy nowy obiekt DigitalSignature przy użyciu określonego certyfikatu. |
| [`__init__(self, file_path, password)`](/slides/python-net/pl/aspose.slides/digitalsignature/__init__/#str-str) | Tworzy nowy obiekt DigitalSignature przy użyciu określonej ścieżki do pliku certyfikatu i hasła. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`certificate`](/slides/python-net/pl/aspose.slides/digitalsignature/certificate/) | Obiekt certyfikatu użyty do podpisania dokumentu.<br/>            Tylko do odczytu **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/pl/aspose.slides/digitalsignature/is_valid/) | Jeśli ten podpis cyfrowy jest prawidłowy i dokument nie został zmodyfikowany, ta wartość będzie prawdziwa.<br/>            Tylko do odczytu **bool**. |
| [`sign_time`](/slides/python-net/pl/aspose.slides/digitalsignature/sign_time/) | Czas, w którym dokument został podpisany.<br/>            Tylko do odczytu **System.DateTime**. |
| [`comments`](/slides/python-net/pl/aspose.slides/digitalsignature/comments/) | Cel podpisu.<br/>            Do odczytu i zapisu **str**. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)
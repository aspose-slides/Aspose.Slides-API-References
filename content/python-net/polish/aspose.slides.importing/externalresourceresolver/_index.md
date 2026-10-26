---
title: ExternalResourceResolver class
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver klasa

Klasa wywołania zwrotnego używana do rozwiązywania zasobów zewnętrznych podczas importu dokumentów Html, Svg.  
Użycie tego resolvera może stworzyć podatność, gdy dostarczony przez klienta plik HTML lub SVG spowoduje, że oprogramowanie serwera pobierze plik lokalny lub sieciowy. Należy używać ostrożnie. Zaleca się nie podawać ExternalResourceResolver wcale (tylko osadzone obiekty będą odczytywane) lub utworzyć podklasę, która sprawdza, czy określony uri jest prawidłowy.

The ExternalResourceResolver type exposes the following members:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/pl/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/pl/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |

### Zobacz także
* moduł [`aspose.slides.importing`](/slides/python-net/pl/aspose.slides.importing)
* biblioteka [`Aspose.Slides`](/slides/python-net)
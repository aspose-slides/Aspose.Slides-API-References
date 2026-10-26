---
title: HtmlExternalResolver class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET - referencja API
description: 
type: docs
url: /pl/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver klasa

Obiekt wywołania zwrotnego używany przez procedurę importu HTML do uzyskiwania odwoływanych obiektów, takich jak obrazy. Użycie tego resolvera może stworzyć lukę bezpieczeństwa, gdy dostarczony przez klienta plik HTML spowoduje, że oprogramowanie serwera pobierze plik lokalny lub sieciowy. Należy używać ostrożnie. Zaleca się nie określać HtmlExternalResolver wcale (tylko osadzone obiekty zostaną odczytane) lub utworzyć podklasę, która sprawdza, czy podany uri jest prawidłowy.

Typ HtmlExternalResolver udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/pl/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Rozwiązuje bezwzględny URI z bazowego i względnych URI. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/pl/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Mapuje URI na obiekt zawierający rzeczywisty zasób. |

### Zobacz także
* moduł [`aspose.slides.importing`](/slides/python-net/pl/aspose.slides.importing)
* biblioteka [`Aspose.Slides`](/slides/python-net)
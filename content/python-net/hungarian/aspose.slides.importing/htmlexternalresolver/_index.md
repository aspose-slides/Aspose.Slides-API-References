---
title: HtmlExternalResolver class
second_title: Aspose.Slides Pythonhoz a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver osztály

Callback objektum, amelyet a HTML import rutin használ az olyan hivatkozott objektumok, például képek megszerzéséhez.
            Ezen feloldó használata sebezhetőséget okozhat, ha a kliens által biztosított HTML fájl a szerver szoftvert helyi vagy hálózati fájl elérésére készteti. Óvatosan használja. Ajánlott, hogy egyáltalán ne adja meg a HtmlExternalResolver-t (csak a beágyazott objektumok lesznek beolvasva), vagy hozzon létre egy alosztályt, amely ellenőrzi, hogy a megadott URI érvényes-e.

A HtmlExternalResolver típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/hu/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/hu/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |

### Lásd még
* modul [`aspose.slides.importing`](/slides/python-net/hu/aspose.slides.importing)
* könyvtár [`Aspose.Slides`](/slides/python-net)
---
title: ExternalResourceResolver class
second_title: Aspose.Slides a Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver osztály

Callback osztály, amely a külső erőforrások feloldására szolgál a Html, Svg dokumentumok importálása során.  
Ennek a feloldónak a használata sebezhetőséget okozhat, ha a kliens által biztosított HTML vagy SVG fájl miatt a kiszolgáló szoftver helyi vagy hálózati fájlt szerez be.  
Használja óvatosan. Ajánlott, hogy egyáltalán ne adjon meg ExternalResourceResolver-t (csak a beágyazott objektumok lesznek beolvasva), vagy hozzon létre egy olyan alosztályt, amely ellenőrzi, hogy a megadott uri érvényes-e.

Az ExternalResourceResolver típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/hu/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Megoldja az abszolút URI-t a bázis és a relatív URI-k alapján. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/hu/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Leképezi a URI-t egy olyan objektumra, amely a tényleges erőforrást tartalmazza. |

### Lásd még
* modul [`aspose.slides.importing`](/slides/python-net/hu/aspose.slides.importing)
* könyvtár [`Aspose.Slides`](/slides/python-net)
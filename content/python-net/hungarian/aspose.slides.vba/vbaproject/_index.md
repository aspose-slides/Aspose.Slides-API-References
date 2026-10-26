---
title: VbaProject class
second_title: Aspose.Slides a Pythonhoz a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.vba/vbaproject/
---
## VbaProject osztály

A VBA projektet a prezentációs makrókkal képviseli.

A VbaProject típus a következő tagokat biztosítja:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.vba/vbaproject/__init__/#) | Ez a konstruktor új VBA projektet hoz létre a semmiből.<br/>            A projekt 1252 Windows Latin 1 (ANSI) kódlapon lesz létrehozva |
| [`__init__(self, data)`](/slides/python-net/hu/aspose.slides.vba/vbaproject/__init__/#bytes) | Ez a konstruktor VBA projektet tölt be az OLE konténer bináris ábrázolásából. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`name`](/slides/python-net/hu/aspose.slides.vba/vbaproject/name/) | Visszaadja a VBA projekt nevét.<br/>            Csak olvasható **str**. |
| [`modules`](/slides/python-net/hu/aspose.slides.vba/vbaproject/modules/) | Visszaadja a VBA projektben található összes modul listáját.<br/>            Csak olvasható [`IVbaModuleCollection`](/slides/python-net/hu/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/hu/aspose.slides.vba/vbaproject/references/) | Visszaadja a VBA projektben található összes hivatkozás listáját.<br/>            Csak olvasható [`IVbaReferenceCollection`](/slides/python-net/hu/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/hu/aspose.slides.vba/vbaproject/is_password_protected/) | Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez.<br/>            Csak olvasható **bool**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/hu/aspose.slides.vba/vbaproject/to_binary/#) | Visszaadja a VBA projekt bináris ábrázolását OLE konténerként |

### Lásd még
* modul [`aspose.slides.vba`](/slides/python-net/hu/aspose.slides.vba)
* könyvtár [`Aspose.Slides`](/slides/python-net)
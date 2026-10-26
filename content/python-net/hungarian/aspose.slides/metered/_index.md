---
title: Metered class
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/metered/
---
## Metered osztály

Módszereket biztosít a metered kulcs beállításához.

A Metered típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/metered/__init__/#) | Új példányt hoz létre ebből az osztályból. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/hu/aspose.slides/metered/set_metered_key/#str-str) | Beállítja a metered nyilvános és privát kulcsot.<br/>            Ha metered licencet vásárol, az alkalmazás indításakor ezt az API-t kell meghívni, általában ez elegendő. <br/>            Azonban ha folyamatosan sikertelen a fogyasztási adatok feltöltése és meghaladja a 24 órát, a licenc értékelési állapotra lesz állítva, <br/>            ennek elkerülése érdekében rendszeresen ellenőrizze a licenc állapotát, ha értékelési állapotú, hívja újra ezt az API-t. |
| [`get_consumption_quantity()`](/slides/python-net/hu/aspose.slides/metered/get_consumption_quantity/#) | Lekéri a fogyasztási fájl méretét |
| [`get_consumption_credit()`](/slides/python-net/hu/aspose.slides/metered/get_consumption_credit/#) | Lekéri a fogyasztási kreditet |
| [`get_product_name(self)`](/slides/python-net/hu/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/hu/aspose.slides/metered/is_metered_licensed/#) | Ellenőrzi, hogy a metered licencelt-e |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
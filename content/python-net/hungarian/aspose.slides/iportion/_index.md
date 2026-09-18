---
title: IPortion class
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/iportion/
---
## IPortion osztály

Egy szövegrészletet reprezentál egy szöveg bekezdésen belül.

Az IPortion típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`portion_format`](/slides/python-net/hu/aspose.slides/iportion/portion_format/) | Visszaadja a formázási objektumot, amely olyan kifejezetten beállított formázási tulajdonságokat tartalmaz a szövegrészlethez, anélkül, hogy öröklődés alkalmazásra kerülne.<br/>            Csak olvasható [`IPortionFormat`](/slides/python-net/hu/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/hu/aspose.slides/iportion/text/) | Lekéri vagy beállítja egy részlet egyszerű szövegét.<br/>            Olvasás/írás **str**. |
| [`field`](/slides/python-net/hu/aspose.slides/iportion/field/) | Visszaadja ennek a részletnek a mezőjét.<br/>            Csak olvasható [`IField`](/slides/python-net/hu/aspose.slides/ifield). |
| [`slide`](/slides/python-net/hu/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/iportion/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/hu/aspose.slides/iportion/add_field/#ifieldtype) | Átalakítja ezt a részletet automatikusan frissített mezővé. |
| [`add_field(self, internal_string)`](/slides/python-net/hu/aspose.slides/iportion/add_field/#str) | Átalakítja ezt a részletet automatikusan frissített mezővé. |
| [`remove_field(self)`](/slides/python-net/hu/aspose.slides/iportion/remove_field/#) | Átalakítja ezt a mező részletet egyszerű részletté. |
| [`get_rect(self)`](/slides/python-net/hu/aspose.slides/iportion/get_rect/#) | Lekéri a részletet körülvevő téglalap koordinátáit. A téglalap tartalmazza a részletben lévő összes sor szövegét, beleértve az üres sorokat is. |
| [`get_coordinates(self)`](/slides/python-net/hu/aspose.slides/iportion/get_coordinates/#) | Lekéri a részlet elejének koordinátáit. A pont X koordinátája a részlet kezdetét jelöli az első karaktertől, beleértve a bal oldali befogást. A Y koordináta tartalmazza a felső befogást. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
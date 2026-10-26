---
title: Portion class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides/portion/
---
## Portion osztály

Egy szövegbekezdésen belüli szövegrészletet képvisel.

A Portion típus a következő tagokat teszi közzé:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/portion/__init__/#) | Inicializál egy új példányt a Portion osztályból. |
| [`__init__(self, str)`](/slides/python-net/hu/aspose.slides/portion/__init__/#str) | Inicializál egy új példányt a Portion osztályból. |
| [`__init__(self, portion)`](/slides/python-net/hu/aspose.slides/portion/__init__/#portion) | Inicializál egy új példányt a Portion osztályból. |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/hu/aspose.slides/portion/portion_format/) | Visszaad egy formázási objektumot, amely a szövegrészletre explicit beállított formázási tulajdonságokat tartalmazza, öröklődés nélkül alkalmazva.<br/>            Csak olvasható [`IPortionFormat`](/slides/python-net/hu/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/hu/aspose.slides/portion/text/) | Lekéri vagy beállítja egy részlet egyszerű szövegét.<br/>            Olvasás/írás **str**. |
| [`field`](/slides/python-net/hu/aspose.slides/portion/field/) | Visszaad ennek a részletnek egy mezőt.<br/>            Csak olvasható [`IField`](/slides/python-net/hu/aspose.slides/ifield). |
| [`slide`](/slides/python-net/hu/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/portion/presentation/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/hu/aspose.slides/portion/add_field/#ifieldtype) | Átalakítja ezt a részletet egy automatikusan frissített mezővé. |
| [`add_field(self, internal_string)`](/slides/python-net/hu/aspose.slides/portion/add_field/#str) | Átalakítja ezt a részletet egy automatikusan frissített mezővé. |
| [`remove_field(self)`](/slides/python-net/hu/aspose.slides/portion/remove_field/#) | Átalakítja ezt a mező részletet egy egyszerű részletté. |
| [`get_rect(self)`](/slides/python-net/hu/aspose.slides/portion/get_rect/#) | Lekéri a részletet határoló téglalap koordinátáit. A téglalap tartalmazza a részletben lévő összes sor szövegét<br/>            beleértve az üres sorokat. |
| [`get_coordinates(self)`](/slides/python-net/hu/aspose.slides/portion/get_coordinates/#) | Lekéri a részlet kezdetének koordinátáit. A pont X koordinátája a <br/>            részlet kezdetét jelöli az első karaktertől, beleértve a bal oldali távolságot. A Y koordináta <br/>            tartalmazza a felső oldali távolságot. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
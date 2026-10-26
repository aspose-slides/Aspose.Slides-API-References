---
title: IChartCategoryCollection class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection osztály

A [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory) gyűjteményt képviseli

Az IChartCategoryCollection típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`use_cells`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/use_cells/) | Ha igaz, akkor a munkalap a kategóriák tárolására kerül felhasználásra (ez az eset több szintű kategóriákat támogat).<br/>            Ha hamis, akkor a munkalap NEM kerül felhasználásra az értékek tárolásához (és ez az eset nem támogatja a <br/>            több szintű kategóriákat).<br/>            Írás/olvasás **bool**. |
| [`grouping_level_count`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Visszaadja a használt kategória-csoportosítási szintek számát.<br/>            Több mint egy, ha több szintű kategóriákról van szó.<br/>            Csak olvasható **int**. |

A megadott indexű elemet adja vissza.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Ha a kategória létezik a gyűjteményben, visszaadja. Egyébként új diagramkategóriát hoz létre a <br/>            [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) alapján, és hozzáadja a gyűjteményhez. |
| [`add(self, value)`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/add/#any) | Új [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez. |
| [`index_of(self, value)`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Keres a megadott [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory)-ra, és visszaadja a teljes gyűjteményben első előfordulásának nulla alapú indexét |
| [`remove(self, value)`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Eltávolítja a megadott értéket. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Eltávolítja az adott indexű elemet. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection/clear/#) | Eltávolítja a gyűjtemény összes elemét. |

### Lásd még
* osztály [`IChartCategory`](/slides/python-net/hu/aspose.slides.charts/ichartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)
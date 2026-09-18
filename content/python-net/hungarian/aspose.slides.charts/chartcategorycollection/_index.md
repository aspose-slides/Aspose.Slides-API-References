---
title: ChartCategoryCollection class
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection osztály

A [`ChartCategory`](/slides/python-net/hu/aspose.slides.charts/chartcategory) gyűjteményét képviseli.

A ChartCategoryCollection típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`use_cells`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/use_cells/) | Ha igaz, akkor munkalapot használnak a kategóriák tárolására (ez az eset több szintű kategóriákat támogat).<br/>            Ha hamis, akkor a munkalap NEM használatos az értékek tárolására (és ez az eset nem támogatja a <br/>            több szintű kategóriákat).<br/>            Olvasás/írás **bool**. |
| [`grouping_level_count`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Visszaadja a használt kategória-csoportosítási szintek számát.<br/>            Több, mint egy a több szintű kategóriák esetén.<br/>            Csak olvasható **int**. |

Lekéri a megadott indexű elemet.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Ha a kategória létezik a gyűjteményben, visszaadja. Ellenkező esetben új diagramkategóriát hoz létre a <br/>            [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell) alapján, és hozzáadja a gyűjteményhez. |
| [`add(self, value)`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/add/#any) | Új [`ChartCategory`](/slides/python-net/hu/aspose.slides.charts/chartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez. |
| [`index_of(self, value)`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Keres a megadott [`ChartCategory`](/slides/python-net/hu/aspose.slides.charts/chartcategory) között, és visszaadja a nullától indexelt első előfordulás helyét a teljes Gyűjteményben. |
| [`remove(self, value)`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Eltávolítja a megadott értéket. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Eltávolítja a megadott indexű elemet. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.charts/chartcategorycollection/clear/#) | Eltávolítja a gyűjtemény összes elemét. |

### Lásd még
* osztály [`ChartCategory`](/slides/python-net/hu/aspose.slides.charts/chartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)
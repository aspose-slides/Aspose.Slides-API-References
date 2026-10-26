---
title: ChartCategory class
second_title: Aspose.Slides Python számára .NET-en keresztül API-referenciája
description: 
type: docs
url: /hu/aspose.slides.charts/chartcategory/
---
## ChartCategory osztály

Represents chart categories.

The ChartCategory type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`use_cell`](/slides/python-net/hu/aspose.slides.charts/chartcategory/use_cell/) | Ha igaz, akkor az AsCell tulajdonság aktív. Más szóval, a munkalap a <br/>            kategória tárolására szolgál (ez az eset több szintű kategóriát támogat).<br/>            Ha hamis, akkor az AsLiteral tulajdonság aktív. Más szóval, a munkalap NEM használatos <br/>            a kategória tárolására (és ez az eset nem támogat több szintű kategóriákat).<br/>            Csak olvasható **bool**. |
| [`as_cell`](/slides/python-net/hu/aspose.slides.charts/chartcategory/as_cell/) | Visszaadja vagy beállítja az IChartDataCell objektumot.<br/>            Ha a kategória több szintű, akkor az IChartDataCell objektum a "0" szinthez van használva.<br/>            Olvasás/írás [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hu/aspose.slides.charts/chartcategory/as_literal/) | Visszaadja vagy beállítja az AsLiteral objektumot.<br/>            Olvasás/írás **any**. |
| [`value`](/slides/python-net/hu/aspose.slides.charts/chartcategory/value/) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot jelenti.<br/>            Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot jelenti.<br/>            Olvasás/írás **any**. |
| [`grouping_levels`](/slides/python-net/hu/aspose.slides.charts/chartcategory/grouping_levels/) | Kezelt tároló a diagramkategória csoportosítási szintek értékeinek.<br/>            Többszintű kategória több mint egy csoportosítási szintet tartalmaz.<br/>            A csoportosítási szintek indexelése nulla-alapú.<br/>            Csak olvasható [`IChartCategoryLevelsManager`](/slides/python-net/hu/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/chartcategory/remove/#) | Eltávolítja a kategóriát a diagramról. |


### Kapcsolódó részek
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)
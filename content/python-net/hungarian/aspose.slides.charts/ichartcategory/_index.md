---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartcategory/
---
## IChartCategory osztály

Represents chart categories.

The IChartCategory type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`use_cell`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/use_cell/) | Ha igaz, akkor az AsCell property aktuális. Más szóval, a munkalap a <br/>            kategória tárolására szolgál (ez az eset több szintű kategóriát támogat).<br/>            Ha hamis, akkor az AsLiteral property aktuális. Más szóval, a munkalap NEM használatos <br/>            a kategória tárolására (és ez az eset nem támogat több szintű kategóriákat).<br/>            Csak olvasható **bool**. |
| [`as_cell`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/as_cell/) | Visszaadja vagy beállítja az IChartDataCell objektumot.<br/>            Ha a kategória több szintű, akkor a "0" szinthez használt IChartDataCell objektum.<br/>            Olvasás/írás [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/as_literal/) | Visszaadja vagy beállítja az AsLiteral értéket, ha a UseCell hamis.<br/>            Olvasás/írás **any**. |
| [`value`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/value/) | Ha a UseCell igaz, akkor ez a property az AsCell.Value property-t jelenti.<br/>            Ha a UseCell hamis, akkor ez a property az AsLiteral property-t jelenti.<br/>            Olvasás/írás **any**. |
| [`grouping_levels`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/grouping_levels/) | A diagramkategória csoportosítási szintek értékeinek kezelt tárolója.<br/>            Többszintű kategória egynél több csoportosítási szintet tartalmaz.<br/>            A csoportosítási szintek indexelése nulláról indul.<br/>            Csak olvasható [`IChartCategoryLevelsManager`](/slides/python-net/hu/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/remove/#) | Eltávolítja a kategóriát a diagramról. |


### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)
---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartcategory/
---
## ChartCategory osztály

A diagramkategóriákat képviseli.

A ChartCategory típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`use_cell`](/slides/python-net/hu/aspose.slides.charts/chartcategory/use_cell/) | Ha igaz, akkor az AsCell tulajdonság aktuális. Más szóval, a munkalapot a <br/>            kategória tárolására használják (ez az eset több szintű kategóriát támogat).<br/>            Ha hamis, akkor az AsLiteral tulajdonság aktuális. Más szóval, a munkalapot NEM használják <br/>            a kategória tárolására (és ez az eset nem támogat több szintű kategóriákat).<br/>            Csak olvasható **bool**. |
| [`as_cell`](/slides/python-net/hu/aspose.slides.charts/chartcategory/as_cell/) | Visszaadja vagy beállítja az IChartDataCell objektumot.<br/>            Ha a kategória több szintű, akkor az "0" szinthez használt IChartDataCell objektumot.<br/>            Olvasás/írás [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hu/aspose.slides.charts/chartcategory/as_literal/) | Visszaadja vagy beállítja az AsLiteral objektumot.<br/>            Olvasás/írás **any**. |
| [`value`](/slides/python-net/hu/aspose.slides.charts/chartcategory/value/) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli.<br/>            Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli.<br/>            Olvasás/írás **any**. |
| [`grouping_levels`](/slides/python-net/hu/aspose.slides.charts/chartcategory/grouping_levels/) | Kezelt tároló a diagramkategória csoportosítási szintek értékeire.<br/>            A több szintű kategória egynél több csoportosítási szintet tartalmaz.<br/>            A csoportosítási szintek indexelése nulláral kezdődik.<br/>            Csak olvasható [`IChartCategoryLevelsManager`](/slides/python-net/hu/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/hu/aspose.slides.charts/chartcategory/cached_value/) | Lekéri a diagramkategória gyorsítótárazott értékét.<br/>            Csak olvasható [`ICachedChartValue`](/slides/python-net/hu/aspose.slides.charts/icachedchartvalue). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/chartcategory/remove/#) | Eltávolítja a kategóriát a diagramról. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)
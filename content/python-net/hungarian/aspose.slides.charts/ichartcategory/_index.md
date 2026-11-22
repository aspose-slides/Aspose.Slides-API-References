---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartcategory/
---
## IChartCategory osztály

Képviseli a diagramkategóriákat.

Az IChartCategory típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`use_cell`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/use_cell/) | Ha igaz, akkor az AsCell property aktuális. Más szóval, a worksheet-et használják a <br/>            storing category (this case supports a multi-level category).<br/>            Ha hamis, akkor az AsLiteral property aktuális. Más szóval, a worksheet NEM használják <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            Csak olvasható **bool**. |
| [`as_cell`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/as_cell/) | Visszaadja vagy beállítja az IChartDataCell object.<br/>            Ha a category multi-level, akkor a \"0\" szinthez használt IChartDataCell object.<br/>            Olvasás/írás [`IChartDataCell`](/slides/python-net/hu/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/as_literal/) | Visszaadja vagy beállítja az AsLiteral, ha UseCell hamis.<br/>            Olvasás/írás **any**. |
| [`value`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/value/) | Ha UseCell igaz, akkor ez a property az AsCell.Value property-t jelenti.<br/>            Ha UseCell hamis, akkor ez a property az AsLiteral property-t jelenti.<br/>            Olvasás/írás **any**. |
| [`cached_value`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/cached_value/) | Lekéri a diagramkategória gyorsítótárazott értékét.<br/>            Csak olvasható [`ICachedChartValue`](/slides/python-net/hu/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/grouping_levels/) | Kezelt tároló a diagramkategória csoportosítási szintjeinek értékeihez.<br/>            Többszintű kategória több, mint egy csoportosítási szintet tartalmaz.<br/>            A csoportosítási szintek indexelése nullától indul.<br/>            Csak olvasható [`IChartCategoryLevelsManager`](/slides/python-net/hu/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metódusok

| Metóda | Leírás |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/ichartcategory/remove/#) | Eltávolítja a kategóriát a diagramról. |


### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)
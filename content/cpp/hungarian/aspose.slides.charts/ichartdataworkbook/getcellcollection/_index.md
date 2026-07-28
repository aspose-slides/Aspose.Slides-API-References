---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a cellák halmazát.
type: docs
weight: 27
url: /hu/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) metódus

A cellák halmazát adja vissza.

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) formula, például "Sheet1!$A$2:$A$5". |
| skipHiddenCells | **bool** | Ha igaz, akkor a metódus egy olyan gyűjteményt ad vissza, amely nem tartalmaz rejtett cellákat. |

### Visszatérési érték

Cellák halmaza [IChartCellCollection](../../ichartcellcollection/)

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartCellCollection](../../ichartcellcollection/)
* Osztály [String](../../../system/string/)
* Osztály [IChartDataWorkbook](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)
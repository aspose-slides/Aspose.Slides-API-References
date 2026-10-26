---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt die Sammlung von Arbeitsblättern des Diagrammdaten-Arbeitsbuchs dar.
type: docs
url: /de/com.aspose.slides/ichartdataworksheetcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Stellt die Sammlung von Arbeitsblättern des Diagrammdaten-Arbeitsbuchs dar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Arbeitsblatt anhand des Index zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Gibt das Arbeitsblatt anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Arbeitsblatts in der Sammlung. |

**Rückgabewert:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instanz von IChartDataWorksheet.
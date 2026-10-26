---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides dla Java – Referencja API
description: Reprezentuje kolekcję arkuszy danych wykresu.
type: docs
url: /pl/com.aspose.slides/ichartdataworksheetcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Reprezentuje kolekcję arkuszy danych wykresu.

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
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca arkusz kalkulacyjny według indeksu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Zwraca arkusz kalkulacyjny według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks arkusza w kolekcji. |

**Zwraca:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instancja IChartDataWorksheet.
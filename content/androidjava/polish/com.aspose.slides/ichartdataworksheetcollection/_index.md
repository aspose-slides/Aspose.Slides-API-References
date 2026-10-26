---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje kolekcję arkuszy skoroszytu danych wykresu.
type: docs
url: /pl/com.aspose.slides/ichartdataworksheetcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Reprezentuje kolekcję arkuszy skoroszytu danych wykresu.

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
| [get_Item(int index)](#get-Item-int-) | Zwraca arkusz roboczy według indeksu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Zwraca arkusz roboczy według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks arkusza w kolekcji. |

**Zwraca:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instancja IChartDataWorksheet.
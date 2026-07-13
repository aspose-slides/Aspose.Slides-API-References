---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar samlingen av arbetsblad i diagramdataboken.
type: docs
url: /sv/com.aspose.slides/ichartdataworksheetcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Representerar samlingen av arbetsblad i diagramdataboken.

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar arbetsbladet efter index. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


Returnerar arbetsbladet efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för arbetsbladet i samlingen. |

**Returnerar:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instans av IChartDataWorksheet.
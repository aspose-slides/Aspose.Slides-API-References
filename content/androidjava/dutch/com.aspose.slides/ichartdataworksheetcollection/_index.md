---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de verzameling werkbladen van de grafiekgegevens-werkmap voor.
type: docs
url: /nl/com.aspose.slides/ichartdataworksheetcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Stelt de verzameling werkbladen van de grafiekgegevens-werkmap voor.

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

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het werkblad op basis van de index. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


Retourneert het werkblad op basis van de index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het werkblad in de verzameling. |

**Retour:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instantie van de IChartDataWorksheet.
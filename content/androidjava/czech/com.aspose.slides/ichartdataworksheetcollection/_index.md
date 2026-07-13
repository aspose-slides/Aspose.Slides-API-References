---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Representuje kolekci listů sešitu s daty grafu.
type: docs
url: /cs/com.aspose.slides/ichartdataworksheetcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Representuje kolekci listů sešitu s daty grafu.

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

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací list podle indexu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


Vrací list podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index listu v kolekci. |

**Vrací:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instance třídy IChartDataWorksheet.
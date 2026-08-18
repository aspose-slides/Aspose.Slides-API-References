---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides Java API Referenciája
description: A diagramadatok munkafüzetének munkalapjainak gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/ichartdataworksheetcollection/
---
**Összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

A diagramadatok munkafüzetének munkalapjainak gyűjteményét reprezentálja.

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
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a munkalapot index alapján. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Visszaadja a munkalapot index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A munkalap indexe a gyűjteményben. |

**Visszatérési érték:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Az IChartDataWorksheet példánya.
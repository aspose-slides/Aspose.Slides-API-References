---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides for Android Java API hivatkozás
description: Ábrázolja a diagramadat-munkafüzet munkalapjainak gyűjteményét.
type: docs
url: /hu/com.aspose.slides/ichartdataworksheetcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Ábrázolja a diagramadat-munkafüzet munkalapjainak gyűjteményét.

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

**Visszaad:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Az IChartDataWorksheet példánya.
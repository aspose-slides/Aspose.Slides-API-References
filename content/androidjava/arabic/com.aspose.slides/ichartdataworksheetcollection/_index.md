---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة أوراق العمل في دفتر بيانات المخطط.
type: docs
url: /ar/com.aspose.slides/ichartdataworksheetcollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

يمثل مجموعة أوراق العمل في دفتر بيانات المخطط.

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
## الطرق

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع ورقة العمل حسب الفهرس. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

يرجع ورقة العمل حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس ورقة العمل في المجموعة. |

**القيمة المرجعة:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - مثال لـ IChartDataWorksheet.
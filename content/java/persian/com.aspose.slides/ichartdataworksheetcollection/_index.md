---
title: IChartDataWorksheetCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش مجموعه‌ای از کاربرگ‌های کتاب‌کار داده‌های نمودار.
type: docs
url: /fa/com.aspose.slides/ichartdataworksheetcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

نمایش مجموعه‌ای از کاربرگ‌های کتاب‌کار داده‌های نمودار.

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
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برگ کاری را بر اساس اندیس برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


برگ کاری را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس کاربرگ در مجموعه. |

**بازگشت:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - نمونه‌ای از IChartDataWorksheet.
---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشگر مجموعه‌ای از ورق‌کارهای کتاب کار داده‌های نمودار.
type: docs
url: /fa/com.aspose.slides/ichartdataworksheetcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

نمایشگر مجموعه‌ی ورق‌کارهای کتاب کار داده‌های نمودار.

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
| [get_Item(int index)](#get-Item-int-) | ورق کار را بر اساس ایندکس برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

ورق کار را بر اساس ایندکس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس ورق کار در مجموعه. |

**بازگشت:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - نمونه‌ای از IChartDataWorksheet.
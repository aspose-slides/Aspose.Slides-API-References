---
title: LegendEntryCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مجموعه افسانه‌ها.
type: docs
url: /fa/com.aspose.slides/legendentrycollection/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)  
```
public class LegendEntryCollection implements ILegendEntryCollection
```

نمایش مجموعه افسانه‌ها.  
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ویژگی‌های ورودی افسانه‌ای که مربوط به Chart.ChartData.Series[0].DataPoints[index] است را دریافت می‌کند، در صورتی که نوع نمودار از این فهرست باشد: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا مربوط به Chart.ChartData.Series[index] برای سایر انواع نمودار. |
| [getCount()](#getCount--) | تعداد ورودی‌های افسانه‌ای را دریافت می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

ویژگی‌های ورودی افسانه‌ای که مربوط به Chart.ChartData.Series[0].DataPoints[index] است را دریافت می‌کند، در صورتی که نوع نمودار از این فهرست باشد: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا مربوط به Chart.ChartData.Series[index] برای سایر انواع نمودار.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد ورودی‌های افسانه‌ای را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**
int
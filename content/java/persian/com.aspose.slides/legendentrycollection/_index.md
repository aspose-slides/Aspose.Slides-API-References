---
title: LegendEntryCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه افسانه‌ها.
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

نمایانگر مجموعهٔ افسانه‌ها.

## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ویژگی‌های ورودی افسانه‌ای که به Chart.ChartData.Series[0].DataPoints[index] مربوط می‌شود را در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا به Chart.ChartData.Series[index] برای سایر انواع نمودار، دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد ورودی‌های افسانه‌ای را دریافت می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

ویژگی‌های ورودی افسانه‌ای که به Chart.ChartData.Series[0].DataPoints[index] مربوط می‌شود را در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا به Chart.ChartData.Series[index] برای سایر انواع نمودار، دریافت می‌کند.

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

تعداد ورودی‌های افسانه‌ای را دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int
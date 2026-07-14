---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: نمایانگر مجموعهٔ افسانه‌ها.
type: docs
url: /fa/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

نمایانگر مجموعهٔ افسانه‌ها.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | خصوصیات ورودی افسانه که به Chart.ChartData.Series[0].DataPoints[index] مربوط می‌شود در صورت وجود نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا مربوط به Chart.ChartData.Series[index] برای انواع دیگر نمودارها. |
| [getCount()](#getCount--) | تعداد واقعی عناصری که در مجموعه موجود است را بر می‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


خصوصیات ورودی افسانه که به Chart.ChartData.Series[0].DataPoints[index] مربوط می‌شود در صورت وجود نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا مربوط به Chart.ChartData.Series[index] برای انواع دیگر نمودارها.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد واقعی عناصری که در مجموعه موجود است را بر می‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
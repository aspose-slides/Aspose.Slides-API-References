---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents legends collection.
type: docs
url: /fa/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

نمایانگر مجموعهٔ افسانه‌ها.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ویژگی‌های ورودی افسانه‌ای که به Chart.ChartData.Series[0].DataPoints[index] مربوط می‌شود را در صورت‌وجود نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا مربوط به Chart.ChartData.Series[index] برای انواع دیگر نمودار، دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد عناصری که واقعاً در مجموعه وجود دارند را دریافت می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


ویژگی‌های ورودی افسانه‌ای که به Chart.ChartData.Series[0].DataPoints[index] مربوط می‌شود را در صورت‌وجود نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie؛ یا مربوط به Chart.ChartData.Series[index] برای انواع دیگر نمودار، دریافت می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد عناصری که واقعاً در مجموعه وجود دارند را دریافت می‌کند. int فقط-خواندنی.

**Returns:**
int
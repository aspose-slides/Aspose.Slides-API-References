---
title: LegendEntryCollection
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示圖例集合。
type: docs
url: /zh-hant/com.aspose.slides/legendentrycollection/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

表示圖例集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得對應於 Chart.ChartData.Series[0].DataPoints[index] 的圖例項目屬性（圖表類型為下列之一：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）或對應於其他圖表類型的 Chart.ChartData.Series[index]。 |
| [getCount()](#getCount--) | 取得圖例項目的數量。 |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


取得對應於 Chart.ChartData.Series[0].DataPoints[index] 的圖例項目屬性（圖表類型為下列之一：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）或對應於其他圖表類型的 Chart.ChartData.Series[index]。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


取得圖例項目的數量。唯讀 int。

**傳回值:**
int
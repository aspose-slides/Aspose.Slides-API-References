---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖例集合。
type: docs
url: /zh-hant/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

表示圖例集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得對應於 Chart.ChartData.Series[0].DataPoints[index] 的圖例項目屬性，當圖表類型屬於以下清單時：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie；或對於其他圖表類型，對應於 Chart.ChartData.Series[index]。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

取得對應於 Chart.ChartData.Series[0].DataPoints[index] 的圖例項目屬性，當圖表類型屬於以下清單時：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie；或對於其他圖表類型，對應於 Chart.ChartData.Series[index]。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中實際包含的元素數量。唯讀 int。

**返回值：**
int
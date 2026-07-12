---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: データポイントレベルのコンテナです。
type: docs
url: /ja/com.aspose.slides/chartdatapointlevelsmanager/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

データポイントレベルのコンテナです。Treeamp と Sunburst 系列に適用されます。データポイントレベルのインデックスはゼロベースです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 指定されたレベルの IChartDataPointLevel オブジェクトを返します。 |
| [getCount()](#getCount--) | データポイントレベルの数を返します。 |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

指定されたレベルの IChartDataPointLevel オブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| level | int |  |

**戻り値:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

データポイントレベルの数を返します。

**戻り値:**
int
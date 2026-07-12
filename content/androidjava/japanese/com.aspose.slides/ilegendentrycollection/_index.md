---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents legends collection.
type: docs
url: /ja/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

凡例コレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | このリストのチャートタイプの場合、Chart.ChartData.Series[0].DataPoints[index] に対応する凡例エントリのプロパティを取得します: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; その他のチャートタイプの場合は Chart.ChartData.Series[index] に対応するものを取得します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

このリストのチャートタイプの場合、Chart.ChartData.Series[0].DataPoints[index] に対応する凡例エントリのプロパティを取得します: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; その他のチャートタイプの場合は Chart.ChartData.Series[index] に対応するものを取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
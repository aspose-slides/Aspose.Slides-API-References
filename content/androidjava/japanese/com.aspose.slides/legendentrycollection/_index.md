---
title: LegendEntryCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 凡例コレクションを表します。
type: docs
url: /ja/com.aspose.slides/legendentrycollection/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)  
```
public class LegendEntryCollection implements ILegendEntryCollection
```

凡例コレクションを表します。  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Chart.ChartData.Series[0].DataPoints[index] が対象となるチャートタイプが次の一覧にある場合: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; それ以外のチャートタイプの場合は Chart.ChartData.Series[index] に対応する凡例エントリのプロパティを取得します。 |
| [getCount()](#getCount--) | 凡例エントリの数を取得します。 |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Chart.ChartData.Series[0].DataPoints[index] が対象となるチャートタイプが次の一覧にある場合: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; それ以外のチャートタイプの場合は Chart.ChartData.Series[index] に対応する凡例エントリのプロパティを取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

凡例エントリの数を取得します。読み取り専用 int。

**戻り値:**
int
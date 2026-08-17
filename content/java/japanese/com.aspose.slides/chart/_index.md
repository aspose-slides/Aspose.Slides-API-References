---
title: Chart
second_title: Aspose.Slides for Java API リファレンス
description: スライド上のグラフィックチャートを表します。
type: docs
url: /ja/com.aspose.slides/chart/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

スライド上のグラフィックチャートを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | チャート要素の実際の値を計算します。 |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 表示されているセルのみがプロットされているかどうかを判断します。 |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 表示されているセルのみがプロットされているかどうかを判断します。 |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | チャートで空白セルをプロットする方法を取得または設定します。 |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | チャートで空白セルをプロットする方法を取得または設定します。 |
| [getChartData()](#getChartData--) | チャートに関連付けられたリンクまたは埋め込みデータに関する情報を取得します。 |
| [hasTitle()](#hasTitle--) | チャートに表示可能なタイトルがあるかどうかを判断します。 |
| [setTitle(boolean value)](#setTitle-boolean-) | チャートに表示可能なタイトルがあるかどうかを判断します。 |
| [getChartTitle()](#getChartTitle--) | チャートのタイトルを取得または設定します。 |
| [hasDataTable()](#hasDataTable--) | チャートにデータテーブルがあるかどうかを判断します。 |
| [setDataTable(boolean value)](#setDataTable-boolean-) | チャートにデータテーブルがあるかどうかを判断します。 |
| [hasLegend()](#hasLegend--) | チャートに凡例があるかどうかを判断します。 |
| [setLegend(boolean value)](#setLegend-boolean-) | チャートに凡例があるかどうかを判断します。 |
| [getLegend()](#getLegend--) | チャートの凡例を取得または設定します。 |
| [getChartDataTable()](#getChartDataTable--) | チャートのデータテーブルを取得します。 |
| [getStyle()](#getStyle--) | チャートのスタイルを取得または設定します。 |
| [setStyle(int value)](#setStyle-int-) | チャートのスタイルを取得または設定します。 |
| [getType()](#getType--) | チャートの種類を取得または設定します。 |
| [setType(int value)](#setType-int-) | チャートの種類を取得または設定します。 |
| [getPlotArea()](#getPlotArea--) | チャートのプロット領域を表します。 |
| [getRotation3D()](#getRotation3D--) | チャートの3D回転を取得します。 |
| [getBackWall()](#getBackWall--) | 3Dチャートの背面壁の書式を変更できるオブジェクトを取得します。 |
| [getSideWall()](#getSideWall--) | 3Dチャートの側面壁の書式を変更できるオブジェクトを取得します。 |
| [getFloor()](#getFloor--) | 3Dチャートの基底面の書式を変更できるオブジェクトを取得します。 |
| [getTextFormat()](#getTextFormat--) | チャートのテキスト書式を取得します。 |
| [createThemeEffective()](#createThemeEffective--) | このチャートの有効なテーマを取得します。 |
| [getThemeManager()](#getThemeManager--) | テーママネージャーを取得します。 |
| [getUserShapes()](#getUserShapes--) | チャート上に描画される形状を指定します。 |
| [getAxes()](#getAxes--) | チャートの軸へのアクセスを提供します。 |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | チャートの最大値を超えるデータラベルを表示するかどうかを指定します。 |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | チャートの最大値を超えるデータラベルを表示するかどうかを指定します。 |
| [hasRoundedCorners()](#hasRoundedCorners--) | チャート領域が角丸になるように指定します。 |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | チャート領域が角丸になるように指定します。 |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

チャート要素の実際の値を計算します。実際の値には IActualLayout インターフェイスを実装する要素の位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) と実際の軸の値 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) が含まれます。

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

表示されているセルのみがプロットされているかどうかを判断します。非表示セルもプロットする場合は false を指定します。**読み書き可能** ブール値。

**戻り値:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

表示されているセルのみがプロットされているかどうかを判断します。非表示セルもプロットする場合は false を指定します。**読み書き可能** ブール値。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

チャートで空白セルをプロットする方法を取得または設定します。**読み書き可能** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**戻り値:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

チャートで空白セルをプロットする方法を取得または設定します。**読み書き可能** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

チャートに関連付けられたリンクまたは埋め込みデータに関する情報を取得します。**読み取り専用** [IChartData](../../com.aspose.slides/ichartdata)。

**戻り値:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

チャートに表示可能なタイトルがあるかどうかを判断します。**読み書き可能** ブール値。

**戻り値:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

チャートに表示可能なタイトルがあるかどうかを判断します。**読み書き可能** ブール値。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

チャートのタイトルを取得または設定します。**読み取り専用** [IChartTitle](../../com.aspose.slides/icharttitle)。

**戻り値:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

チャートにデータテーブルがあるかどうかを判断します。**読み書き可能** ブール値。

**戻り値:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

チャートにデータテーブルがあるかどうかを判断します。**読み書き可能** ブール値。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

チャートに凡例があるかどうかを判断します。**読み書き可能** ブール値。

**戻り値:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

チャートに凡例があるかどうかを判断します。**読み書き可能** ブール値。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

チャートの凡例を取得または設定します。**読み取り専用** [ILegend](../../com.aspose.slides/ilegend)。

**戻り値:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

チャートのデータテーブルを取得します。**読み取り専用** [IDataTable](../../com.aspose.slides/idatatable)。

**戻り値:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

チャートのスタイルを取得または設定します。**読み書き可能** [StyleType](../../com.aspose.slides/styletype)。

**戻り値:**  
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

チャートのスタイルを取得または設定します。**読み書き可能** [StyleType](../../com.aspose.slides/styletype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

チャートの種類を取得または設定します。**読み書き可能** [ChartType](../../com.aspose.slides/charttype)。

**戻り値:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

チャートの種類を取得または設定します。**読み書き可能** [ChartType](../../com.aspose.slides/charttype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

チャートのプロット領域を取得します。**読み取り専用** [IChartPlotArea](../../com.aspose.slides/ichartplotarea)。

**戻り値:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

チャートの3D回転を取得します。**読み取り専用** [IRotation3D](../../com.aspose.slides/irotation3d)。

**戻り値:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

3Dチャートの背面壁の書式を変更できるオブジェクトを取得します。**読み取り専用** [IChartWall](../../com.aspose.slides/ichartwall)。

**戻り値:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

3Dチャートの側面壁の書式を変更できるオブジェクトを取得します。**読み取り専用** [IChartWall](../../com.aspose.slides/ichartwall)。

**戻り値:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

3Dチャートの基底面の書式を変更できるオブジェクトを取得します。**読み取り専用** [IChartWall](../../com.aspose.slides/ichartwall)。

**戻り値:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

チャートのテキスト書式を取得します。次のタイプには適用できません: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)。**読み取り専用** [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

このチャートの有効なテーマを取得します。

**戻り値:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

テーママネージャーを取得します。**読み取り専用** [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**戻り値:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

チャート上に描画される形状を指定します。**読み取り専用** [IGroupShape](../../com.aspose.slides/igroupshape)。

**戻り値:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

チャートの軸へのアクセスを提供します。**読み取り専用** [IAxesManager](../../com.aspose.slides/iaxesmanager)。

**戻り値:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

チャートの最大値を超えるデータラベルを表示するかどうかを指定します。**読み書き可能** ブール値。

**戻り値:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

チャートの最大値を超えるデータラベルを表示するかどうかを指定します。**読み書き可能** ブール値。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

チャート領域が角丸になるように指定します。**読み書き可能** ブール値。

**戻り値:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

チャート領域が角丸になるように指定します。**読み書き可能** ブール値。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

チャートを取得します。**読み取り専用** [IChart](../../com.aspose.slides/ichart)。

**戻り値:**  
[IChart](../../com.aspose.slides/ichart)
---
title: IChart
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライド上のグラフィックチャートを表します。
type: docs
url: /ja/com.aspose.slides/ichart/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

スライド上のグラフィックチャートを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 表示されているセルのみがプロットされるかどうかを決定します。 |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 表示されているセルのみがプロットされるかどうかを決定します。 |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | チャート上の空白セルのプロット方法を取得または設定します。 |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | チャート上の空白セルのプロット方法を取得または設定します。 |
| [getChartData()](#getChartData--) | チャートに関連付けられたリンクされたデータまたは埋め込みデータに関する情報を取得します。 |
| [hasTitle()](#hasTitle--) | チャートに表示可能なタイトルがあるかどうかを決定します。 |
| [setTitle(boolean value)](#setTitle-boolean-) | チャートに表示可能なタイトルがあるかどうかを決定します。 |
| [getChartTitle()](#getChartTitle--) | チャートのタイトルを取得または設定します。読み取り専用 [IChartTitle](../../com.aspose.slides/icharttitle)。 |
| [hasDataTable()](#hasDataTable--) | チャートにデータテーブルがあるかどうかを決定します。 |
| [setDataTable(boolean value)](#setDataTable-boolean-) | チャートにデータテーブルがあるかどうかを決定します。 |
| [hasLegend()](#hasLegend--) | チャートに凡例があるかどうかを決定します。 |
| [setLegend(boolean value)](#setLegend-boolean-) | チャートに凡例があるかどうかを決定します。 |
| [getLegend()](#getLegend--) | チャートの凡例を取得または設定します。 |
| [getChartDataTable()](#getChartDataTable--) | チャートのデータテーブルを取得します。 |
| [getStyle()](#getStyle--) | チャートのスタイルを取得または設定します。 |
| [setStyle(int value)](#setStyle-int-) | チャートのスタイルを取得または設定します。 |
| [getType()](#getType--) | チャートのタイプを取得または設定します。 |
| [setType(int value)](#setType-int-) | チャートのタイプを取得または設定します。 |
| [getPlotArea()](#getPlotArea--) | チャートのプロット領域を表します。 |
| [getRotation3D()](#getRotation3D--) | チャートの3D回転を取得します。 |
| [getBackWall()](#getBackWall--) | 3Dチャートの背面壁の書式を変更できるオブジェクトを取得します。 |
| [getSideWall()](#getSideWall--) | 3Dチャートの側壁の書式を変更できるオブジェクトを取得します。 |
| [getFloor()](#getFloor--) | 3Dチャートの床の書式を変更できるオブジェクトを取得します。 |
| [getUserShapes()](#getUserShapes--) | チャート上に描画される形状を指定します。 |
| [getAxes()](#getAxes--) | チャート軸へのアクセスを提供します。 |
| [validateChartLayout()](#validateChartLayout--) | チャート要素の実際の値を計算します。 |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | チャートの最大値を超えるデータラベルを表示するかどうかを指定します。 |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | チャートの最大値を超えるデータラベルを表示するかどうかを指定します。 |
| [hasRoundedCorners()](#hasRoundedCorners--) | チャート領域に角丸を適用するかどうかを指定します。 |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | チャート領域に角丸を適用するかどうかを指定します。 |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

表示されているセルのみがプロットされるかどうかを決定します。False を指定すると、表示セルと非表示セルの両方がプロットされます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

表示されているセルのみがプロットされるかどうかを決定します。False を指定すると、表示セルと非表示セルの両方がプロットされます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

チャート上の空白セルのプロット方法を取得または設定します。読み取り/書き込み [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**戻り値:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

チャート上の空白セルのプロット方法を取得または設定します。読み取り/書き込み [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

チャートに関連付けられたリンクされたデータまたは埋め込みデータに関する情報を取得します。読み取り専用 [IChartData](../../com.aspose.slides/ichartdata)。

**戻り値:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

チャートに表示可能なタイトルがあるかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

チャートに表示可能なタイトルがあるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

チャートのタイトルを取得または設定します。読み取り専用 [IChartTitle](../../com.aspose.slides/icharttitle)。

**戻り値:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

チャートにデータテーブルがあるかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

チャートにデータテーブルがあるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

チャートに凡例があるかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

チャートに凡例があるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

チャートの凡例を取得または設定します。読み取り専用 [ILegend](../../com.aspose.slides/ilegend)。

**戻り値:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

チャートのデータテーブルを取得します。読み取り専用 [IDataTable](../../com.aspose.slides/idatatable)。

**戻り値:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

チャートのスタイルを取得または設定します。読み取り/書き込み [StyleType](../../com.aspose.slides/styletype)。

**戻り値:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

チャートのスタイルを取得または設定します。読み取り/書き込み [StyleType](../../com.aspose.slides/styletype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

チャートのタイプを取得または設定します。読み取り/書き込み [ChartType](../../com.aspose.slides/charttype)。

**戻り値:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

チャートのタイプを取得または設定します。読み取り/書き込み [ChartType](../../com.aspose.slides/charttype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

チャートのプロット領域を表します。読み取り専用 [IChartPlotArea](../../com.aspose.slides/ichartplotarea)。

**戻り値:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

チャートの3D回転を取得します。読み取り専用 [IRotation3D](../../com.aspose.slides/irotation3d)。

**戻り値:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

3Dチャートの背面壁の書式を変更できるオブジェクトを取得します。読み取り専用 [IChartWall](../../com.aspose.slides/ichartwall)。

**戻り値:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

3Dチャートの側壁の書式を変更できるオブジェクトを取得します。読み取り専用 [IChartWall](../../com.aspose.slides/ichartwall)。

**戻り値:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

3Dチャートの床の書式を変更できるオブジェクトを取得します。読み取り専用 [IChartWall](../../com.aspose.slides/ichartwall)。

**戻り値:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

チャート上に描画される形状を指定します。読み取り専用 [IGroupShape](../../com.aspose.slides/igroupshape)。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

チャート軸へのアクセスを提供します。読み取り専用 [IAxesManager](../../com.aspose.slides/iaxesmanager)。

**戻り値:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

チャート要素の実際の値を計算します。実際の値には IActualLayout インターフェイス (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) を実装する要素の位置および IAxis の実際の軸値 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) が含まれます。
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

チャートの最大値を超えるデータラベルを表示するかどうかを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

チャートの最大値を超えるデータラベルを表示するかどうかを指定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

チャート領域に角丸を適用するかどうかを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

チャート領域に角丸を適用するかどうかを指定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
---
title: ChartSeriesGroup
second_title: Aspose.Slides for Java API リファレンス
description: 系列のグループを表します。
type: docs
url: /ja/com.aspose.slides/chartseriesgroup/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

シリーズのグループを表します。

--------------------

1) ChartSeriesGroupCollection クラスと CombinableSeriesTypesGroup 列挙体の概要と備考をご覧ください。 2) 系列のグループは、グループ内の各系列に共通するいくつかの系列プロパティを含みます（「シリーズ グループ プロパティ」）。 ChartSeriesGroup クラスの「シリーズ グループ プロパティ」は読み取り/書き込み可能です。 「シリーズ グループ プロパティ」の各項目は、ChartSeries クラスで読み取り専用のプロジェクションを持つことができます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | このシリーズ グループの型を返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | このグループのシリーズが二次軸にプロットされているかどうかを示します。 |
| [getSeries()](#getSeries--) | シリーズのコレクションを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUpDownBars()](#getUpDownBars--) | ラインまたは株価チャートの上/下バーへのアクセスを提供します。 |
| [getGapWidth()](#getGapWidth--) | バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。 |
| [setGapWidth(int value)](#setGapWidth-int-) | バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初の円グラフまたはドーナツ グラフのスライスの角度を度単位で取得または設定します（上から時計回り、0〜360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 最初の円グラフまたはドーナツ グラフのスライスの角度を度単位で取得または設定します（上から時計回り、0〜360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツ グラフの穴のサイズを指定します（プロット領域のサイズの 0〜90 パーセント）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ドーナツ グラフの穴のサイズを指定します（プロット領域のサイズの 0〜90 パーセント）。 |
| [getOverlap()](#getOverlap--) | 2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイ チャートまたはバー・オブ・パイ チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5〜200 パーセント）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | パイ・オブ・パイ チャートまたはバー・オブ・パイ チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5〜200 パーセント）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブル チャートでバブルサイズの値がどのように表現されるかを指定します。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | バブル チャートでバブルサイズの値がどのように表現されるかを指定します。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定するために使用される値を指定します。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定する方法を指定します。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定する方法を指定します。 |
| [isColorVaried()](#isColorVaried--) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [hasSeriesLines()](#hasSeriesLines--) | チャートに系列線がある場合は True。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | チャートに系列線がある場合は True。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines 形式を指定します。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブル チャートのスケール係数を指定します（デフォルトサイズの 0〜300 パーセント）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | バブル チャートのスケール係数を指定します（デフォルトサイズの 0〜300 パーセント）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割を持つパイ・オブ・パイ またはバー・オブ・パイ チャートのカスタム分割情報です。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getType() {#getType--}
```
public final int getType()
```

このシリーズ グループの型を返します。読み取り専用 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**戻り値:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

このグループのシリーズが二次軸にプロットされているかどうかを示します。読み取り専用 boolean。

**戻り値:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

シリーズのコレクションを返します。読み取り専用 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**戻り値:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

ラインまたは株価チャートの上/下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**戻り値:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。読み取り/書き込み int。

**戻り値:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。読み取り/書き込み int。

**戻り値:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

最初の円グラフまたはドーナツ グラフのスライスの角度を度単位で取得または設定します（上から時計回り、0〜360 度）。読み取り/書き込み int。

**戻り値:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

最初の円グラフまたはドーナツ グラフのスライスの角度を度単位で取得または設定します（上から時計回り、0〜360 度）。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ドーナツ グラフの穴のサイズを指定します（プロット領域のサイズの 0〜90 パーセント）。読み取り/書き込み byte。

**戻り値:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

ドーナツ グラフの穴のサイズを指定します（プロット領域のサイズの 0〜90 パーセント）。読み取り/書き込み byte。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。-100%: 最大の間隔（バーは完全に分離）。0%: バーは重なりも間隔もなく並びます。100%: 最大の重なり（バーは完全に重なる）。このプロパティは読み取り/書き込み byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // オーバーラップを55%に設定
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。-100%: 最大の間隔（バーは完全に分離）。0%: バーは重なりも間隔もなく並びます。100%: 最大の重なり（バーは完全に重なる）。このプロパティは読み取り/書き込み byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // オーバーラップを55%に設定
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

パイ・オブ・パイ またはバー・オブ・パイ チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5〜200 パーセント）。読み取り/書き込み int。

**戻り値:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

パイ・オブ・パイ またはバー・オブ・パイ チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5〜200 パーセント）。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

バブル チャートでバブルサイズの値がどのように表現されるかを指定します。読み取り/書き込み [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**戻り値:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

バブル チャートでバブルサイズの値がどのように表現されるかを指定します。読み取り/書き込み [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと共に使用されます。読み取り/書き込み double。

**戻り値:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと共に使用されます。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定する方法を指定します。読み取り/書き込み [PieSplitType](../../com.aspose.slides/piesplittype)。

**戻り値:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

パイ・オブ・パイ またはバー・オブ・パイ チャートで、第2の円またはバーに含めるデータポイントを決定する方法を指定します。読み取り/書き込み [PieSplitType](../../com.aspose.slides/piesplittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

チャートに系列線がある場合は True。スタック バーおよび OfPie チャートに適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

チャートに系列線がある場合は True。スタック バーおよび OfPie チャートに適用されます。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines 形式を指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで適用されます。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

バブル チャートのスケール係数を指定します（デフォルトサイズの 0〜300 パーセント）。読み取り/書き込み int。

**戻り値:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

バブル チャートのスケール係数を指定します（デフォルトサイズの 0〜300 パーセント）。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割を持つパイ・オブ・パイ またはバー・オブ・パイ チャートのカスタム分割情報です。第2の円またはバーに描画されるデータポイントを含みます。読み取り専用 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

**戻り値:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat の親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
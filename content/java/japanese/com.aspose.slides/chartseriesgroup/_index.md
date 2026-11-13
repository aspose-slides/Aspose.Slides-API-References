---
title: ChartSeriesGroup
second_title: Aspose.Slides の Java API リファレンス
description: シリーズのグループを表します。
type: docs
url: /ja/com.aspose.slides/chartseriesgroup/
---
**継承:**  
java.lang.Object

**実装されている全インターフェイス:**  
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject  
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

シリーズのグループを表します。

--------------------

1) ChartSeriesGroupCollection クラスと CombinableSeriesTypesGroup 列挙体の概要と Remarks を参照してください。  
2) シリーズのグループには、グループ内の各シリーズに共通するいくつかのシリーズ プロパティ（「シリーズ グループ プロパティ」）が含まれます。ChartSeriesGroup クラスの「シリーズ グループ プロパティ」は読み取り/書き込み可能です。各「シリーズ グループ プロパティ」には、ChartSeries クラスで読み取り専用の投影が存在する場合があります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | このシリーズ グループの型を返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | このグループのシリーズが副軸にプロットされているかどうかを示します。 |
| [getSeries()](#getSeries--) | シリーズのコレクションを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUpDownBars()](#getUpDownBars--) | 折れ線または株価チャートの上下バーへのアクセスを提供します。 |
| [getGapWidth()](#getGapWidth--) | 棒または列クラスター間の間隔を取得または設定します（棒または列幅のパーセンテージ）。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 棒または列クラスター間の間隔を取得または設定します（棒または列幅のパーセンテージ）。 |
| [getGapDepth()](#getGapDepth--) | 3D チャートのデータシリーズ間の距離を取得または設定します（マーカー幅のパーセンテージ）。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D チャートのデータシリーズ間の距離を取得または設定します（マーカー幅のパーセンテージ）。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0〜90%）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0〜90%）。 |
| [getOverlap()](#getOverlap--) | 2D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイまたはバー・オブ・パイチャートの第 2 の円または棒のサイズを、第 1 の円のサイズのパーセンテージで指定します（5 から 200%）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | パイ・オブ・パイまたはバー・オブ・パイチャートの第 2 の円または棒のサイズを、第 1 の円のサイズのパーセンテージで指定します（5 から 200%）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャートでバブルサイズ値がどのように表現されるかを指定します。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | バブルチャートでバブルサイズ値がどのように表現されるかを指定します。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定するために使用される値を指定します。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定する方法を指定します。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定する方法を指定します。 |
| [isColorVaried()](#isColorVaried--) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [hasSeriesLines()](#hasSeriesLines--) | true if chart has series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | true if chart has series lines. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines の書式を指定します。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300%）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300%）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割を持つパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報です。 |
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

このグループのシリーズが副軸にプロットされているかどうかを示します。読み取り専用 boolean。

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

折れ線または株価チャートの上下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**戻り値:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

棒または列クラスター間の間隔を取得または設定します（棒または列幅のパーセンテージ）。値は 0 から 500 の範囲である必要があります。読み取り/書き込み int。

--------------------

このプロパティは次のタイプのシリーズに適用されます: 棒サブタイプ ([ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) メソッドも参照)、列サブタイプ ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) メソッドも参照)、[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)、[ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)、[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)、[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)、[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)、[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)。

**戻り値:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

棒または列クラスター間の間隔を取得または設定します（棒または列幅のパーセンテージ）。値は 0 から 500 の範囲である必要があります。読み取り/書き込み int。

--------------------

このプロパティは次のタイプのシリーズに適用されます: 棒サブタイプ ([ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) メソッドも参照)、列サブタイプ ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) メソッドも参照)、[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)、[ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)、[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)、[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)、[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)、[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D チャートのデータシリーズ間の距離を取得または設定します（マーカー幅のパーセンテージ）。値は 0 から 500 の範囲である必要があります。読み取り/書き込み int。

--------------------

このプロパティは次のタイプのシリーズに適用されます: 3D 棒および列サブタイプ ([ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) メソッドも参照)、[ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)、[ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)、[ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)、[ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)。

**戻り値:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D チャートのデータシリーズ間の距離を取得または設定します（マーカー幅のパーセンテージ）。値は 0 から 500 の範囲である必要があります。読み取り/書き込み int。

--------------------

このプロパティは次のタイプのシリーズに適用されます: 3D 棒および列サブタイプ ([ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) メソッドも参照)、[ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)、[ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)、[ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)、[ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。読み取り/書き込み int。

**戻り値:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。読み取り/書き込み int。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0〜90%）。読み取り/書き込み byte。

**戻り値:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0〜90%）。読み取り/書き込み byte。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。- -100%: 最大間隔（棒は完全に分離）。- 0%: 棒は重なりも間隔もなく並んで配置。- 100%: 最大重なり（棒は完全に互いに重なる）。このプロパティは読み取り/書き込み byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 重なりを55%に設定
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

2D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。- -100%: 最大間隔（棒は完全に分離）。- 0%: 棒は重なりも間隔もなく並んで配置。- 100%: 最大重なり（棒は完全に互いに重なる）。このプロパティは読み取り/書き込み byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 重なりを55%に設定
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

パイ・オブ・パイまたはバー・オブ・パイチャートの第 2 の円または棒のサイズを、第 1 の円のサイズのパーセンテージで指定します（5 から 200%）。読み取り/書き込み int。

**戻り値:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートの第 2 の円または棒のサイズを、第 1 の円のサイズのパーセンテージで指定します（5 から 200%）。読み取り/書き込み int。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

バブルチャートでバブルサイズ値がどのように表現されるかを指定します。読み取り/書き込み [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**戻り値:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

バブルチャートでバブルサイズ値がどのように表現されるかを指定します。読み取り/書き込み [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み取り/書き込み double。

**戻り値:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み取り/書き込み double。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定する方法を指定します。読み取り/書き込み [PieSplitType](../../com.aspose.slides/piesplittype)。

**戻り値:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第 2 の円または棒に含まれるかを決定する方法を指定します。読み取り/書き込み [PieSplitType](../../com.aspose.slides/piesplittype)。

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

チャートにシリーズラインがある場合は true。スタック棒および OfPie チャートに適用されます。読み取り/書き込み boolean。

**戻り値:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

チャートにシリーズラインがある場合は true。スタック棒および OfPie チャートに適用されます。読み取り/書き込み boolean。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines の書式を指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose の各チャートタイプで適用されます。

**戻り値:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300%）。読み取り/書き込み int。

**戻り値:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300%）。読み取り/書き込み int。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割を持つパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報です。第 2 の円または棒に描画されるデータポイントを含みます。読み取り専用 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

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
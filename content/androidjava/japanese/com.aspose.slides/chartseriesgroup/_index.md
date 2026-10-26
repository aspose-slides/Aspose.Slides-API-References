---
title: ChartSeriesGroup
second_title: Aspose.Slides for Android via Java API リファレンス
description: シリーズのグループを表します。
type: docs
url: /ja/com.aspose.slides/chartseriesgroup/
---
**継承:**  
java.lang.Object

**実装されたインターフェイス:**  
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject  
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

シリーズのグループを表します。

--------------------

1) ChartSeriesGroupCollection クラスと CombinableSeriesTypesGroup 列挙体の概要と備考をご覧ください。  
2) シリーズのグループには、グループ内の各シリーズで共通のいくつかのシリーズプロパティがあります（「series group properties」）。ChartSeriesGroup クラスの「Series group properties」は読み書き可能です。「series group properties」の各項目は、ChartSeries クラスで読み取り専用の投影を持つことができます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | このシリーズグループの型を返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | このグループのシリーズが副軸にプロットされているかどうかを示します。 |
| [getSeries()](#getSeries--) | シリーズのコレクションを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUpDownBars()](#getUpDownBars--) | Line または Stock チャートの上下バーへのアクセスを提供します。 |
| [getGapWidth()](#getGapWidth--) | バーまたは列のクラスター間の間隔を、バーまたは列の幅のパーセンテージで指定します。 |
| [setGapWidth(int value)](#setGapWidth-int-) | バーまたは列のクラスター間の間隔を、バーまたは列の幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初の円グラフまたはドーナツグラフのスライスの角度を度で取得または設定します（上から時計回りに、0 から 360 度まで）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 最初の円グラフまたはドーナツグラフのスライスの角度を度で取得または設定します（上から時計回りに、0 から 360 度まで）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0%〜90% の範囲で設定可能）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0%〜90% の範囲で設定可能）。 |
| [getOverlap()](#getOverlap--) | 2 次元チャートでバーと列がどの程度重なるかをパーセンテージで指定します（-100% から 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 2 次元チャートでバーと列がどの程度重なるかをパーセンテージで指定します（-100% から 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5%〜200% の範囲で設定可能）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5%〜200% の範囲で設定可能）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。 |
| [isColorVaried()](#isColorVaried--) | シリーズ内の各データマーカーが異なる色を持つように指定します。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | シリーズ内の各データマーカーが異なる色を持つように指定します。 |
| [hasSeriesLines()](#hasSeriesLines--) | チャートにシリーズラインがある場合は true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | チャートにシリーズラインがある場合は true。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines の書式を指定します。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲で設定可能）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲で設定可能）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割を使用したパイ・オブ・パイチャートまたはバー・オブ・パイチャートのカスタム分割情報です。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### getType() {#getType--}
```
public final int getType()
```

このシリーズグループの型を返します。読み取り専用 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

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

Line または Stock チャートの上下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**戻り値:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

バーまたは列のクラスター間の間隔を、バーまたは列の幅のパーセンテージで指定します。読み書き int。

**戻り値:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

バーまたは列のクラスター間の間隔を、バーまたは列の幅のパーセンテージで指定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。読み書き int。

**戻り値:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

最初の円グラフまたはドーナツグラフのスライスの角度を度で取得または設定します（上から時計回りに、0 から 360 度まで）。読み書き int。

**戻り値:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

最初の円グラフまたはドーナツグラフのスライスの角度を度で取得または設定します（上から時計回りに、0 から 360 度まで）。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0%〜90% の範囲で設定可能）。読み書き byte。

**戻り値:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0%〜90% の範囲で設定可能）。読み書き byte。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2 次元チャートでバーと列がどの程度重なるかをパーセンテージで指定します（-100% から 100%）。-100%: 最大間隔（バーは完全に分離）。0%: バーは並んだままで重なりも間隔もなし。100%: 最大重なり（バーは完全に重なる）。このプロパティは読み書き byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // オーバーラップを55%に設定します
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

2 次元チャートでバーと列がどの程度重なるかをパーセンテージで指定します（-100% から 100%）。-100%: 最大間隔（バーは完全に分離）。0%: バーは並んだままで重なりも間隔もなし。100%: 最大重なり（バーは完全に重なる）。このプロパティは読み書き byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // オーバーラップを55%に設定します
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

パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5%〜200% の範囲で設定可能）。読み書き int。

**戻り値:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5%〜200% の範囲で設定可能）。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

バブルチャートでバブルサイズの値がどのように表現されるかを指定します。読み書き [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**戻り値:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

バブルチャートでバブルサイズの値がどのように表現されるかを指定します。読み書き [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み書き double。

**戻り値:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み書き double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。読み書き [PieSplitType](../../com.aspose.slides/piesplittype)。

**戻り値:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。読み書き [PieSplitType](../../com.aspose.slides/piesplittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

シリーズ内の各データマーカーが異なる色を持つように指定します。読み書き boolean。

**戻り値:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

シリーズ内の各データマーカーが異なる色を持つように指定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

チャートにシリーズラインがある場合は true。スタックバーおよび OfPie チャートに適用されます。読み書き boolean。

**戻り値:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

チャートにシリーズラインがある場合は true。スタックバーおよび OfPie チャートに適用されます。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines の書式を指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで使用されます。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲で設定可能）。読み書き int。

**戻り値:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲で設定可能）。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割を使用したパイ・オブ・パイチャートまたはバー・オブ・パイチャートのカスタム分割情報です。第2の円またはバーに描画されるデータポイントを含みます。読み取り専用 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

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
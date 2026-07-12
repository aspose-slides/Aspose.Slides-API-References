---
title: IChartSeriesGroup
second_title: Aspose.Slides for Android の Java API リファレンス
description: シリーズのグループを表します。
type: docs
url: /ja/com.aspose.slides/ichartseriesgroup/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

シリーズのグループを表します。

--------------------

1) ChartSeriesGroupCollection クラスと CombinableSeriesTypesGroup 列挙体の概要と注釈を参照してください。2) シリーズのグループは、グループ内の各シリーズに共通のいくつかのシリーズプロパティ（「シリーズ グループ プロパティ」）を含みます。ChartSeriesGroup クラスの「シリーズ グループ プロパティ」は読み取り/書き込み可能です。各「シリーズ グループ プロパティ」は ChartSeries クラスで読み取り専用の投影を持つことができます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | このシリーズ グループの型を返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | このグループのシリーズが二次軸にプロットされているかどうかを示します。 |
| [getSeries()](#getSeries--) | チャートシリーズの読み取り専用コレクションを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUpDownBars()](#getUpDownBars--) | 線グラフまたは株価チャートの上/下バーへのアクセスを提供します。 |
| [getGapWidth()](#getGapWidth--) | バーまたは列のクラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。 |
| [setGapWidth(int value)](#setGapWidth-int-) | バーまたは列のクラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | 3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。 |
| [isColorVaried()](#isColorVaried--) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [hasSeriesLines()](#hasSeriesLines--) | チャートにシリーズラインがある場合は true です。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | チャートにシリーズラインがある場合は true です。 |
| [getOverlap()](#getOverlap--) | 2-D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の範囲）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の範囲）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割が設定されたパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報です。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の範囲）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の範囲）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の範囲）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の範囲）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines のフォーマットを指定します。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャート上でバブルサイズ値がどのように表現されるかを指定します。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | バブルチャート上でバブルサイズ値がどのように表現されるかを指定します。 |

### getType() {#getType--}
```
public abstract int getType()
```

このシリーズ グループの型を返します。読み取り専用 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**戻り値:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

このグループのシリーズが二次軸にプロットされているかどうかを示します。読み取り専用 boolean。

**戻り値:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

チャートシリーズの読み取り専用コレクションを返します。読み取り専用 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**戻り値:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

線グラフまたは株価チャートの上/下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**戻り値:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

バーまたは列のクラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。読み取り/書き込み int。

**戻り値:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

バーまたは列のクラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。読み取り/書き込み int。

**戻り値:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。読み取り/書き込み int。

**戻り値:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

最初の円グラフまたはドーナツチャートのスライスの角度を取得または設定します（度単位、上から時計回り、0 から 360 度）。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

チャートにシリーズラインがある場合は true です。スタックバーおよび OfPie チャートに適用されます。読み取り/書き込み boolean。

**戻り値:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

チャートにシリーズラインがある場合は true です。スタックバーおよび OfPie チャートに適用されます。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。- -100%: 最大間隔（バーは完全に分離）。- 0%: バーは重なりや間隔なしで並列に配置。- 100%: 最大重なり（バーは互いに完全に重なる）。このプロパティは読み取り/書き込み byte です。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 重なりを 55% に設定
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

2-D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。- -100%: 最大間隔（バーは完全に分離）。- 0%: バーは重なりや間隔なしで並列に配置。- 100%: 最大重なり（バーは互いに完全に重なる）。このプロパティは読み取り/書き込み byte です。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 重なりを 55% に設定
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の範囲）。読み取り/書き込み int。

**戻り値:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の範囲）。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み取り/書き込み double。

**戻り値:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。読み取り/書き込み [PieSplitType](../../com.aspose.slides/piesplittype)。

**戻り値:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。読み取り/書き込み [PieSplitType](../../com.aspose.slides/piesplittype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割が設定されたパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報です。第2の円またはバーに描画されるデータポイントを含みます。読み取り専用 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**戻り値:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の範囲）。読み取り/書き込み byte。

**戻り値:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の範囲）。読み取り/書き込み byte。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の範囲）。読み取り/書き込み int。

**戻り値:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の範囲）。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines のフォーマットを指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで適用されます。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

バブルチャート上でバブルサイズ値がどのように表現されるかを指定します。読み取り/書き込み [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**戻り値:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

バブルチャート上でバブルサイズ値がどのように表現されるかを指定します。読み取り/書き込み [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
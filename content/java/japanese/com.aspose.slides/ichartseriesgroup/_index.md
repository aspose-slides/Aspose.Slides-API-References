---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API リファレンス
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

1) ChartSeriesGroupCollection クラスと CombinableSeriesTypesGroup 列挙体の概要と備考を参照してください。 2) シリーズのグループは、グループ内の各シリーズに共通するいくつかのシリーズプロパティを含みます（「series group properties」）。「Series group properties」 in ChartSeriesGroup class は読み書き可能です。Each of 「series group properties」 can have a read-only projection in ChartSeries class.

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | このシリーズグループの型を返します。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | このグループのシリーズが二次軸にプロットされるかどうかを示します。 |
| [getSeries()](#getSeries--) | チャートシリーズの読み取り専用コレクションを返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUpDownBars()](#getUpDownBars--) | 折れ線グラフまたはストックチャートの上/下バーへのアクセスを提供します。 |
| [getGapWidth()](#getGapWidth--) | バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。 |
| [setGapWidth(int value)](#setGapWidth-int-) | バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。 |
| [getGapDepth()](#getGapDepth--) | 3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで返すまたは設定します。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで返すまたは設定します。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 最初の円グラフまたはドーナツチャートのスライスの角度を度単位で取得または設定します（上から時計回り、0 から 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 最初の円グラフまたはドーナツチャートのスライスの角度を度単位で取得または設定します（上から時計回り、0 から 360 度）。 |
| [isColorVaried()](#isColorVaried--) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | シリーズ内の各データマーカーが異なる色を持つことを指定します。 |
| [hasSeriesLines()](#hasSeriesLines--) | チャートに系列線がある場合は true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | チャートに系列線がある場合は true。 |
| [getOverlap()](#getOverlap--) | 2D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。 |
| [getSecondPieSize()](#getSecondPieSize--) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5 から 200%）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5 から 200%）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。 |
| [getPieSplitBy()](#getPieSplitBy--) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | カスタム分割を持つパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報です。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90%）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90%）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300%）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300%）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines の形式を指定します。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。 |

### getType() {#getType--}
```
public abstract int getType()
```

このシリーズグループの型を返します。読み取り専用 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**戻り値:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

このグループのシリーズが二次軸にプロットされるかどうかを示します。読み取り専用 boolean。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

折れ線グラフまたはストックチャートの上/下バーへのアクセスを提供します。読み取り専用 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**戻り値:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。読み書き int。

**戻り値:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージで指定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで返すまたは設定します。読み書き int。

**戻り値:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D チャートのデータシリーズ間の距離を、マーカー幅のパーセンテージで返すまたは設定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

最初の円グラフまたはドーナツチャートのスライスの角度を度単位で取得または設定します（上から時計回り、0 から 360 度）。読み書き int。

**戻り値:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

最初の円グラフまたはドーナツチャートのスライスの角度を度単位で取得または設定します（上から時計回り、0 から 360 度）。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。読み書き boolean。

**戻り値:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

シリーズ内の各データマーカーが異なる色を持つことを指定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

チャートに系列線がある場合は true。スタックドバーおよび OfPie チャートに適用されます。読み書き boolean。

**戻り値:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

チャートに系列線がある場合は true。スタックドバーおよび OfPie チャートに適用されます。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。-100%: 最大間隔（バーは完全に分離）。0%: 重なりや間隔なしで隣接配置。100%: 最大重なり（バーは完全に重なる）。このプロパティは読み書き byte。

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

2D チャートでバーと列がどれだけ重なるかを、パーセンテージ（-100% から 100%）で指定します。-100%: 最大間隔（バーは完全に分離）。0%: 重なりや間隔なしで隣接配置。100%: 最大重なり（バーは完全に重なる）。このプロパティは読み書き byte。

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
public abstract int getSecondPieSize()
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5 から 200%）。読み書き int。

**戻り値:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

パイ・オブ・パイチャートまたはバー・オブ・パイチャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5 から 200%）。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み書き double。

**戻り値:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。読み書き double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。読み書き [PieSplitType](../../com.aspose.slides/piesplittype)。

**戻り値:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

パイ・オブ・パイまたはバー・オブ・パイチャートで、どのデータポイントが第2の円またはバーに属するかを決定する方法を指定します。読み書き [PieSplitType](../../com.aspose.slides/piesplittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

カスタム分割を持つパイ・オブ・パイまたはバー・オブ・パイチャートのカスタム分割情報です。第2の円またはバーに描画されるデータポイントを含みます。読み取り専用 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**戻り値:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90%）。読み書き byte。

**戻り値:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90%）。読み書き byte。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300%）。読み書き int。

**戻り値:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300%）。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines の形式を指定します。HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで適用されます。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

バブルチャートでバブルサイズの値がどのように表現されるかを指定します。読み書き [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**戻り値:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

バブルチャートでバブルサイズの値がどのように表現されるかを指定します。読み書き [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
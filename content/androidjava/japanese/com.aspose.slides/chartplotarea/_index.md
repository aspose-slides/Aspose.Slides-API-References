---
title: ChartPlotArea
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: チャートが描画される矩形を表します。
type: docs
url: /ja/com.aspose.slides/chartplotarea/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

チャートが描画される矩形を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat()](#getFormat--) | プロット領域のフォーマットを返します。 |
| [getX()](#getX--) | プロット領域バウンドボックスの左上隅の x 座標を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 |
| [setX(float value)](#setX-float-) | プロット領域バウンドボックスの左上隅の x 座標を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 |
| [getY()](#getY--) | プロット領域バウンドボックスの左上隅の y 座標を、チャートの高さに対する比率 (0 から 1) として取得または設定します。 |
| [setY(float value)](#setY-float-) | プロット領域バウンドボックスの左上隅の y 座標を、チャートの高さに対する比率 (0 から 1) として取得または設定します。 |
| [getWidth()](#getWidth--) | プロット領域バウンドボックスの幅を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | プロット領域バウンドボックスの幅を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 |
| [getHeight()](#getHeight--) | プロット領域バウンドボックスの高さを、チャートの高さに対する比率 (0 から 1) として取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | プロット領域バウンドボックスの高さを、チャートの高さに対する比率 (0 から 1) として取得または設定します。 |
| [getRight()](#getRight--) | Right. |
| [getBottom()](#getBottom--) | Bottom. |
| [getChart()](#getChart--) | Chart. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | ロケーションの計算方法を定義します: true – 自動的に計算; X、Y、Width、Height プロパティで定義されます。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部 (軸と軸ラベルを除く) でレイアウトするか、外部 (軸と軸ラベルを含む) でレイアウトするかを指定します。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部 (軸と軸ラベルを除く) でレイアウトするか、外部 (軸と軸ラベルを含む) でレイアウトするかを指定します。 |
| [getActualX()](#getActualX--) | チャート要素の実際の x 位置 (左) をチャートの左上隅に対して指定します。 |
| [getActualY()](#getActualY--) | チャート要素の実際の上位置をチャートの左上隅に対して指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


プロット領域のフォーマットを返します。 読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getX() {#getX--}
```
public final float getX()
```


プロット領域バウンドボックスの左上隅の x 座標を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**戻り値:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


プロット領域バウンドボックスの左上隅の x 座標を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


プロット領域バウンドボックスの左上隅の y 座標を、チャートの高さに対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**戻り値:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


プロット領域バウンドボックスの左上隅の y 座標を、チャートの高さに対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


プロット領域バウンドボックスの幅を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**戻り値:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


プロット領域バウンドボックスの幅を、チャートの幅に対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


プロット領域バウンドボックスの高さを、チャートの高さに対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**戻り値:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


プロット領域バウンドボックスの高さを、チャートの高さに対する比率 (0 から 1) として取得または設定します。 読み書き可能 float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```


Right. 読み取り専用 float。

**戻り値:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Bottom. 読み取り専用 float。

**戻り値:**
float
### getChart() {#getChart--}
```
public final IChart getChart()
```


Chart. 読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)
### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```


ロケーションの計算方法を定義します: true – 自動的に計算; X、Y、Width、Height プロパティで定義されます。 読み取り専用 boolean。

**戻り値:**
boolean
### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```


プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部 (軸と軸ラベルを除く) でレイアウトするか、外部 (軸と軸ラベルを含む) でレイアウトするかを指定します。 読み書き可能 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**戻り値:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```


プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部 (軸と軸ラベルを除く) でレイアウトするか、外部 (軸と軸ラベルを含む) でレイアウトするかを指定します。 読み書き可能 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


チャート要素の実際の x 位置 (左) をチャートの左上隅に対して指定します。 実際の値を取得するには IChart.ValidateChartLayout() メソッドを呼び出してください。 読み取り float。

**戻り値:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


チャート要素の実際の上位置をチャートの左上隅に対して指定します。 実際の値を取得するには IChart.ValidateChartLayout() メソッドを呼び出してください。 読み取り float。

**戻り値:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


チャート要素の実際の幅を指定します。 実際の値を取得するには IChart.ValidateChartLayout() メソッドを呼び出してください。 読み取り float。

**戻り値:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


チャート要素の実際の高さを指定します。 実際の値を取得するには IChart.ValidateChartLayout() メソッドを呼び出してください。 読み取り float。

**戻り値:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


FillFormat の親スライドを返します。 読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


FillFormat の親プレゼンテーションを返します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
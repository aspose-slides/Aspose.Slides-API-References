---
title: DataLabel
second_title: Aspose.Slides for Java API リファレンス
description: シリーズのラベルを表します。
type: docs
url: /ja/com.aspose.slides/datalabel/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject  
```
public class DataLabel implements IDataLabel, IDOMObject
```

シリーズのラベルを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel クラスの新しいインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [isVisible()](#isVisible--) | False はデータラベルが表示されないことを意味します (したがってすべての Show*-フラグ (ShowValue, ...) は false です)。 |
| [hide()](#hide--) | すべての Show*-フラグ (ShowValue, ...) を false に設定してデータラベルを非表示にします。 |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベルテキストを返します。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | パラメーター "text" のテキストで TextFrameForOverriding を初期化します。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | リッチ書式テキストを含めることができます。 |
| [getTextFormat()](#getTextFormat--) | テキスト形式を返します。 |
| [getX()](#getX--) | タイトルの x 座標をチャートの幅の割合で取得または設定します。 |
| [setX(float value)](#setX-float-) | タイトルの x 座標をチャートの幅の割合で取得または設定します。 |
| [getY()](#getY--) | タイトルの y 座標をチャートの高さの割合で取得または設定します。 |
| [setY(float value)](#setY-float-) | タイトルの y 座標をチャートの高さの割合で取得または設定します。 |
| [getWidth()](#getWidth--) | タイトルの幅をチャートの幅の割合で取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | タイトルの幅をチャートの幅の割合で取得または設定します。 |
| [getHeight()](#getHeight--) | タイトルの高さをチャートの高さの割合で取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | タイトルの高さをチャートの高さの割合で取得または設定します。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 下。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | データラベルの形式を返します。 |
| [getValueFromCell()](#getValueFromCell--) | ワークブックのデータセルを取得または設定します。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | ワークブックのデータセルを取得または設定します。 |
| [getActualX()](#getActualX--) | チャート要素の実際の x 位置 (左) を、チャート左上隅に対する相対位置で指定します。 |
| [getActualY()](#getActualY--) | チャート要素の実際の上位置を、チャート左上隅に対する相対位置で指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel クラスの新しいインスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 親 ChartDataPoint。 |

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

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False はデータラベルが表示されないことを意味します (したがってすべての Show*-フラグ (ShowValue, ...) は false です)。読み取り専用 boolean 。

--------------------

データラベルが表示されている場合、Hide() メソッドで非表示にできます。ただし、データラベルが表示されていない場合 (IsVisible が false)、Show*-フラグ (ShowValue, ...) を true に設定してデータラベルを表示できます。

**戻り値:**
boolean

### hide() {#hide--}
```
public final void hide()
```

すべての Show*-フラグ (ShowValue, ...) を false に設定してデータラベルを非表示にします。この操作後、IsVisible は false になります。

--------------------

データラベルが表示されていない場合 (IsVisible が false)、Show*-フラグ (ShowValue, ...) を true に設定してデータラベルを表示できます。

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベルテキストを返します。

**戻り値:**
java.lang.String - The java.lang.String object.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

パラメーター "text" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding がすでに初期化されている場合は、単にそのテキストを変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrameForOverriding 用テキスト。 |

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

リッチ書式テキストを含めることができます。このプロパティが null でない場合、この書式テキストはデータラベルの自動生成テキストを上書きします。データラベルの自動生成テキストとは、ShowSeriesName、ShowValue、... プロパティで管理され、TextFormatManager.TextFormat プロパティで書式設定されたテキストを指します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

テキスト形式を返します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

タイトルの x 座標をチャートの幅の割合で取得または設定します。読み書き  float 。

**戻り値:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

タイトルの x 座標をチャートの幅の割合で取得または設定します。読み書き  float 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

タイトルの y 座標をチャートの高さの割合で取得または設定します。読み書き  float 。

**戻り値:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

タイトルの y 座標をチャートの高さの割合で取得または設定します。読み書き  float 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

タイトルの幅をチャートの幅の割合で取得または設定します。読み書き  float 。

**戻り値:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

タイトルの幅をチャートの幅の割合で取得または設定します。読み書き  float 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

タイトルの高さをチャートの高さの割合で取得または設定します。読み書き  float 。

**戻り値:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

タイトルの高さをチャートの高さの割合で取得または設定します。読み書き  float 。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右。読み取り専用  float 。

**戻り値:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

下。読み取り専用  float 。

**戻り値:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

データラベルの形式を返します。読み取り専用 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**戻り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

ワークブックのデータセルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

ワークブックのデータセルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

チャート要素の実際の x 位置（左）を、チャート左上隅に対する相対位置で指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。読み取り  float 。

**戻り値:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

チャート要素の実際の上位置を、チャート左上隅に対する相対位置で指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。読み取り  float 。

**戻り値:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

チャート要素の実際の幅を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。読み取り  float 。

**戻り値:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

チャート要素の実際の高さを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。読み取り  float 。

**戻り値:**
float

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
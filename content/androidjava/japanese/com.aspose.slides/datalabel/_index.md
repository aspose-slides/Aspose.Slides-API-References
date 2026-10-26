---
title: DataLabel
second_title: Aspose.Slides for Android の Java API リファレンス
description: シリーズラベルを表します。
type: docs
url: /ja/com.aspose.slides/datalabel/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

シリーズ ラベルを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel クラスの新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [isVisible()](#isVisible--) | False はデータ ラベルが表示されないことを意味し、すべての Show*-フラグ (ShowValue, ...) が false です。 |
| [hide()](#hide--) | すべての Show*-フラグ (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。 |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | リッチ フォーマットのテキストを含めることができます。 |
| [getTextFormat()](#getTextFormat--) | テキスト形式を返します。 |
| [getX()](#getX--) | タイトルの x 座標をチャートの幅の比率として取得または設定します。 |
| [setX(float value)](#setX-float-) | タイトルの x 座標をチャートの幅の比率として取得または設定します。 |
| [getY()](#getY--) | タイトルの y 座標をチャートの高さの比率として取得または設定します。 |
| [setY(float value)](#setY-float-) | タイトルの y 座標をチャートの高さの比率として取得または設定します。 |
| [getWidth()](#getWidth--) | タイトルの幅をチャートの幅の比率として取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | タイトルの幅をチャートの幅の比率として取得または設定します。 |
| [getHeight()](#getHeight--) | タイトルの高さをチャートの高さの比率として取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | タイトルの高さをチャートの高さの比率として取得または設定します。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 下。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | データ ラベル形式を返します。 |
| [getValueFromCell()](#getValueFromCell--) | ワークブック データ セルを取得または設定します。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | ワークブック データ セルを取得または設定します。 |
| [getActualX()](#getActualX--) | チャート要素の実際の x 位置（左）を、チャートの左上隅に対する相対位置で指定します。 |
| [getActualY()](#getActualY--) | チャート要素の実際の上位置を、チャートの左上隅に対する相対位置で指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel クラスの新しいインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 親 ChartDataPoint。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用の IDOMObject。

**返り値:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを返します。読み取り専用の [IChart](../../com.aspose.slides/ichart)。

**返り値:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False はデータ ラベルが表示されないことを意味し、すべての Show*-フラグ (ShowValue, ...) が false です。読み取り専用の boolean 。

**返り値:**
boolean

データ ラベルが表示されている場合は Hide() メソッドで非表示にできます。データ ラベルが表示されていない場合 (IsVisible が false) は、Show*-フラグ (ShowValue, ...) を true に設定して表示できます。

### hide() {#hide--}
```
public final void hide()
```

すべての Show*-フラグ (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。この後、IsVisible は false になります。

データ ラベルが表示されていない場合 (IsVisible が false) は、Show*-フラグ (ShowValue, ...) を true に設定して表示できます。

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。

**返り値:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

パラメータ "text" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding がすでに初期化されている場合は、単にそのテキストを変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrameForOverriding 用のテキスト。 |

**返り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

リッチ フォーマットされたテキストを含めることができます。このプロパティが null でない場合、このフォーマットされたテキスト値はデータ ラベルの自動生成テキストを上書きします。自動生成テキストとは、ShowSeriesName、ShowValue、... プロパティで管理され、TextFormatManager.TextFormat プロパティでフォーマットされたテキストのことです。読み取り専用の [ITextFrame](../../com.aspose.slides/itextframe)。

**返り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

テキスト形式を返します。読み取り専用の [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

タイトルの x 座標をチャートの幅の比率として取得または設定します。読み書き可能な float 。

**返り値:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

タイトルの x 座標をチャートの幅の比率として取得または設定します。読み書き可能な float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

タイトルの y 座標をチャートの高さの比率として取得または設定します。読み書き可能な float 。

**返り値:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

タイトルの y 座標をチャートの高さの比率として取得または設定します。読み書き可能な float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

タイトルの幅をチャートの幅の比率として取得または設定します。読み書き可能な float 。

**返り値:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

タイトルの幅をチャートの幅の比率として取得または設定します。読み書き可能な float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

タイトルの高さをチャートの高さの比率として取得または設定します。読み書き可能な float 。

**返り値:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

タイトルの高さをチャートの高さの比率として取得または設定します。読み書き可能な float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

右。読み取り専用の float 。

**返り値:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

下。読み取り専用の float 。

**返り値:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

データ ラベル形式を返します。読み取り専用の [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返り値:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**返り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

チャート要素の実際の x 位置（左）を、チャートの左上隅に対する相対位置で指定します。実際の値を取得するには、IChart.ValidateChartLayout() メソッドを事前に呼び出してください。読み取り専用の float 。

**返り値:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

チャート要素の実際の上位置を、チャートの左上隅に対する相対位置で指定します。実際の値を取得するには、IChart.ValidateChartLayout() メソッドを事前に呼び出してください。読み取り専用の float 。

**返り値:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

チャート要素の実際の幅を指定します。実際の値を取得するには、IChart.ValidateChartLayout() メソッドを事前に呼び出してください。読み取り専用の float 。

**返り値:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

チャート要素の実際の高さを指定します。実際の値を取得するには、IChart.ValidateChartLayout() メソッドを事前に呼び出してください。読み取り専用の float 。

**返り値:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat の親スライドを返します。読み取り専用の [BaseSlide](../../com.aspose.slides/baseslide)。

**返り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat の親プレゼンテーションを返します。読み取り専用の [IPresentation](../../com.aspose.slides/ipresentation)。

**返り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
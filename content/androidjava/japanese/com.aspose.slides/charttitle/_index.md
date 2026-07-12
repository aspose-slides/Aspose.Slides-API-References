---
title: ChartTitle
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: チャートタイトルのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/charttitle/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IChartTitle](../../com.aspose.slides/icharttitle), com.aspose.slides.IDOMObject  
```
public class ChartTitle implements IChartTitle, IDOMObject
```

チャートタイトルのプロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | タイトルの x 座標をチャートの幅の割合として取得または設定します。 |
| [setX(float value)](#setX-float-) | タイトルの x 座標をチャートの幅の割合として取得または設定します。 |
| [getY()](#getY--) | タイトルの y 座標をチャートの高さの割合として取得または設定します。 |
| [setY(float value)](#setY-float-) | タイトルの y 座標をチャートの高さの割合として取得または設定します。 |
| [getWidth()](#getWidth--) | タイトルの幅をチャートの幅の割合として取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | タイトルの幅をチャートの幅の割合として取得または設定します。 |
| [getHeight()](#getHeight--) | タイトルの高さをチャートの高さの割合として取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | タイトルの高さをチャートの高さの割合として取得または設定します。 |
| [getRight()](#getRight--) | 右端。 |
| [getBottom()](#getBottom--) | 下端。 |
| [getOverlay()](#getOverlay--) | 他のチャート要素がタイトルと重なることを許可するかどうかを決定します。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 他のチャート要素がタイトルと重なることを許可するかどうかを決定します。 |
| [getFormat()](#getFormat--) | タイトルの塗りつぶし、線、効果のスタイルを取得します。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | リッチ書式テキストを含めることができます。 |
| [getTextFormat()](#getTextFormat--) | テキスト書式を取得します。 |
| [getActualX()](#getActualX--) | チャート要素の左上隅からの実際の X 位置（左）を指定します。 |
| [getActualY()](#getActualY--) | チャート要素の左上隅からの実際の上位置を指定します。 |
| [getActualWidth()](#getActualWidth--) | チャート要素の実際の幅を指定します。 |
| [getActualHeight()](#getActualHeight--) | チャート要素の実際の高さを指定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを取得します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを取得します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを取得します。 |

### getX() {#getX--}
```
public final float getX()
```

タイトルの x 座標をチャートの幅の割合として取得または設定します。 読み書き可能 float。

**戻り値:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

タイトルの x 座標をチャートの幅の割合として取得または設定します。 読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

タイトルの y 座標をチャートの高さの割合として取得または設定します。 読み書き可能 float。

**戻り値:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

タイトルの y 座標をチャートの高さの割合として取得または設定します。 読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

タイトルの幅をチャートの幅の割合として取得または設定します。 読み書き可能 float。

**戻り値:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

タイトルの幅をチャートの幅の割合として取得または設定します。 読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

タイトルの高さをチャートの高さの割合として取得または設定します。 読み書き可能 float。

**戻り値:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

タイトルの高さをチャートの高さの割合として取得または設定します。 読み書き可能 float。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右端。 読み取り専用 float。

**戻り値:**  
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

下端。 読み取り専用 float。

**戻り値:**  
float

### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```

他のチャート要素がタイトルと重なることを許可するかどうかを決定します。 読み書き可能 boolean。

**戻り値:**  
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```

他のチャート要素がタイトルと重なることを許可するかどうかを決定します。 読み書き可能 boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

タイトルの塗りつぶし、線、効果のスタイルを取得します。 読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**  
[IFormat](../../com.aspose.slides/iformat)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

パラメータ "text" のテキストで TextFrameForOverriding を初期化します。 既に初期化されている場合はテキストを変更します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrameForOverriding のテキスト。 |

**戻り値:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

リッチ書式テキストを含めることができます。 このプロパティが null でない場合、フォーマットされたテキストが自動生成テキストを上書きします。 自動生成テキストはデータラベル、値軸の表示単位ラベル、軸タイトル、チャートタイトル、トレンドラインのラベルの暗黙のプロパティです。 自動生成テキストは IFormattedTextContainer.TextFormat プロパティで書式設定されます。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

テキスト書式を取得します。 読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

チャート要素の左上隅からの実際の X 位置（左）を指定します。 実際の値を取得するには IChart.validateChartLayout() を呼び出してください。 読み取り float。

**戻り値:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

チャート要素の左上隅からの実際の上位置を指定します。 実際の値を取得するには IChart.validateChartLayout() を呼び出してください。 読み取り float。

**戻り値:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

チャート要素の実際の幅を指定します。 実際の値を取得するには IChart.validateChartLayout() を呼び出してください。 読み取り float。

**戻り値:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

チャート要素の実際の高さを指定します。 実際の値を取得するには IChart.validateChartLayout() を呼び出してください。 読み取り float。

**戻り値:**  
float

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを取得します。 読み取り専用 IDOMObject。

**戻り値:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを取得します。 読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat の親スライドを取得します。 読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat の親プレゼンテーションを取得します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**  
[IPresentation](../../com.aspose.slides/ipresentation)
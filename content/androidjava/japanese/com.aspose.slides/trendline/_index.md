---
title: Trendline
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: クラスはチャート系列のトレンドラインを表します
type: docs
url: /ja/com.aspose.slides/trendline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

このクラスはチャート系列のトレンドラインを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | トレンドラインの名前を取得または設定します。 |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | トレンドラインの名前を取得または設定します。 |
| [getTrendlineType()](#getTrendlineType--) | トレンドラインの種類を取得または設定します。 |
| [setTrendlineType(int value)](#setTrendlineType-int-) | トレンドラインの種類を取得または設定します。 |
| [getFormat()](#getFormat--) | トレンドラインの書式を表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | トレンドラインの書式を表します。 |
| [getBackward()](#getBackward--) | トレンドラインが系列データの前に拡張するカテゴリ数（または散布図の単位）を指定します。 |
| [setBackward(double value)](#setBackward-double-) | トレンドラインが系列データの前に拡張するカテゴリ数（または散布図の単位）を指定します。 |
| [getForward()](#getForward--) | トレンドラインが系列データの後に拡張するカテゴリ数（または散布図の単位）を指定します。 |
| [setForward(double value)](#setForward-double-) | トレンドラインが系列データの後に拡張するカテゴリ数（または散布図の単位）を指定します。 |
| [getIntercept()](#getIntercept--) | トレンドラインが y 軸と交差する位置の値を指定します。 |
| [setIntercept(double value)](#setIntercept-double-) | トレンドラインが y 軸と交差する位置の値を指定します。 |
| [getDisplayEquation()](#getDisplayEquation--) | トレンドラインの方程式がチャート上に表示されることを指定します（R2 値と同じラベルに）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | トレンドラインの方程式がチャート上に表示されることを指定します（R2 値と同じラベルに）。 |
| [getOrder()](#getOrder--) | 多項式トレンドラインの次数を指定します。 |
| [setOrder(byte value)](#setOrder-byte-) | 多項式トレンドラインの次数を指定します。 |
| [getPeriod()](#getPeriod--) | 移動平均トレンドラインの期間を指定します。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 移動平均トレンドラインの期間を指定します。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | トレンドラインの決定係数（R²）の値がチャート上に表示されることを指定します（方程式と同じラベルに）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | トレンドラインの決定係数（R²）の値がチャート上に表示されることを指定します（方程式と同じラベルに）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | このトレンドラインに関連する凡例エントリを表します（読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)）。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | リッチ書式のテキストを含めることができます。 |
| [getTextFormat()](#getTextFormat--) | テキスト書式を返します。 |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

トレンドラインの名前を取得または設定します。読み取り/書き込み可能な String。

**戻り値:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

トレンドラインの名前を取得または設定します。読み取り/書き込み可能な String。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

トレンドラインの種類を取得または設定します。読み取り/書き込み可能な [TrendlineType](../../com.aspose.slides/trendlinetype)。

**戻り値:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

トレンドラインの種類を取得または設定します。読み取り/書き込み可能な [TrendlineType](../../com.aspose.slides/trendlinetype)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

トレンドラインの書式を表します。読み取り/書き込み可能な [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

トレンドラインの書式を表します。読み取り/書き込み可能な [IFormat](../../com.aspose.slides/iformat)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

トレンドラインが系列データの前に拡張するカテゴリ数（または散布図の単位）を指定します。散布図および非散布図では、値は非負である必要があります。読み取り/書き込み可能な double。

**戻り値:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

トレンドラインが系列データの前に拡張するカテゴリ数（または散布図の単位）を指定します。散布図および非散布図では、値は非負である必要があります。読み取り/書き込み可能な double。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

トレンドラインが系列データの後に拡張するカテゴリ数（または散布図の単位）を指定します。散布図および非散布図では、値は非負である必要があります。読み取り/書き込み可能な double。

**戻り値:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

トレンドラインが系列データの後に拡張するカテゴリ数（または散布図の単位）を指定します。散布図および非散布図では、値は非負である必要があります。読み取り/書き込み可能な double。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

トレンドラインが y 軸と交差する位置の値を指定します。このプロパティは、トレンドラインの種類が exp、linear、または poly の場合にのみサポートされます。読み取り/書き込み可能な double。

**戻り値:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

トレンドラインが y 軸と交差する位置の値を指定します。このプロパティは、トレンドラインの種類が exp、linear、または poly の場合にのみサポートされます。読み取り/書き込み可能な double。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

トレンドラインの方程式がチャート上に表示されることを指定します（R2 値と同じラベルに）。読み取り/書き込み可能な boolean。

**戻り値:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

トレンドラインの方程式がチャート上に表示されることを指定します（R2 値と同じラベルに）。読み取り/書き込み可能な boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

多項式トレンドラインの次数を指定します。他のトレンドラインの種類では無視されます。値は 2 から 6 の間である必要があります。読み取り/書き込み可能な byte。

**戻り値:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

多項式トレンドラインの次数を指定します。他のトレンドラインの種類では無視されます。値は 2 から 6 の間である必要があります。読み取り/書き込み可能な byte。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間である必要があります。読み取り/書き込み可能な byte。

**戻り値:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間である必要があります。読み取り/書き込み可能な byte。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

トレンドラインの決定係数（R²）の値がチャート上に表示されることを指定します（方程式と同じラベルに）。読み取り/書き込み可能な boolean。

**戻り値:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

トレンドラインの決定係数（R²）の値がチャート上に表示されることを指定します（方程式と同じラベルに）。読み取り/書き込み可能な boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

このトレンドラインに関連する凡例エントリを表します（読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)）。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

パラメータ "text" のテキストで TextFrameForOverriding を初期化します。既に初期化されている場合はテキストを単に変更します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrameForOverriding のテキスト。 |

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

リッチ書式のテキストを含めることができます。このプロパティが null でない場合、この書式付きテキストはデータラベルの自動生成テキストを上書きします。自動生成テキストとは、ShowSeriesName、ShowValue などのプロパティで管理され、TextFormatManager.TextFormat プロパティで書式設定されたテキストです。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

テキスト書式を返します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

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
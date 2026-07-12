---
title: ITrendline
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: クラスはチャート系列のトレンドラインを表します
type: docs
url: /ja/com.aspose.slides/itrendline/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

クラスはチャート系列のトレンドラインを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | トレンドラインの名前を取得または設定します。 |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | トレンドラインの名前を取得または設定します。 |
| [getTrendlineType()](#getTrendlineType--) | トレンドラインの種類を取得または設定します。 |
| [setTrendlineType(int value)](#setTrendlineType-int-) | トレンドラインの種類を取得または設定します。 |
| [getFormat()](#getFormat--) | トレンドラインの書式を表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | トレンドラインの書式を表します。 |
| [getBackward()](#getBackward--) | トレンドラインが系列データの前に伸びるカテゴリ数（散布図の場合は単位）を指定します。 |
| [setBackward(double value)](#setBackward-double-) | トレンドラインが系列データの前に伸びるカテゴリ数（散布図の場合は単位）を指定します。 |
| [getForward()](#getForward--) | トレンドラインが系列データの後に伸びるカテゴリ数（散布図の場合は単位）を指定します。 |
| [setForward(double value)](#setForward-double-) | トレンドラインが系列データの後に伸びるカテゴリ数（散布図の場合は単位）を指定します。 |
| [getIntercept()](#getIntercept--) | トレンドラインが y 軸と交差する位置の値を指定します。 |
| [setIntercept(double value)](#setIntercept-double-) | トレンドラインが y 軸と交差する位置の値を指定します。 |
| [getDisplayEquation()](#getDisplayEquation--) | トレンドラインの方程式をチャート上に表示するかどうかを指定します（Rsquaredvalue と同じラベルに）。 |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | トレンドラインの方程式をチャート上に表示するかどうかを指定します（Rsquaredvalue と同じラベルに）。 |
| [getOrder()](#getOrder--) | 多項式トレンドラインの次数を指定します。 |
| [setOrder(byte value)](#setOrder-byte-) | 多項式トレンドラインの次数を指定します。 |
| [getPeriod()](#getPeriod--) | 移動平均トレンドラインの期間を指定します。 |
| [setPeriod(byte value)](#setPeriod-byte-) | 移動平均トレンドラインの期間を指定します。 |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | トレンドラインの決定係数(R^2)をチャート上に表示するかどうかを指定します（方程式と同じラベルに）。 |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | トレンドラインの決定係数(R^2)をチャート上に表示するかどうかを指定します（方程式と同じラベルに）。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | このトレンドラインに関連付けられた凡例エントリを表します（読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)）。 |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

トレンドラインの名前を取得または設定します。 読み取り/書き込み String.

**戻り値:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

トレンドラインの名前を取得または設定します。 読み取り/書き込み String.

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

トレンドラインの種類を取得または設定します。 読み取り/書き込み [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int))。

**戻り値:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

トレンドラインの種類を取得または設定します。 読み取り/書き込み [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int))。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

トレンドラインの書式を表します。 読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

トレンドラインの書式を表します。 読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

トレンドラインが系列データの前に伸びるカテゴリ数（散布図の場合は単位）を指定します。 散布図および非散布図では、任意の非負の値を指定できます。 読み取り/書き込み double。

**戻り値:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

トレンドラインが系列データの前に伸びるカテゴリ数（散布図の場合は単位）を指定します。 散布図および非散布図では、任意の非負の値を指定できます。 読み取り/書き込み double。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

トレンドラインが系列データの後に伸びるカテゴリ数（散布図の場合は単位）を指定します。 散布図および非散布図では、任意の非負の値を指定できます。 読み取り/書き込み double。

**戻り値:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

トレンドラインが系列データの後に伸びるカテゴリ数（散布図の場合は単位）を指定します。 散布図および非散布図では、任意の非負の値を指定できます。 読み取り/書き込み double。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

トレンドラインが y 軸と交差する位置の値を指定します。このプロパティは、トレンドラインの種類が exp、linear、または poly の場合にのみサポートされます。 読み取り/書き込み double。

**戻り値:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

トレンドラインが y 軸と交差する位置の値を指定します。このプロパティは、トレンドラインの種類が exp、linear、または poly の場合にのみサポートされます。 読み取り/書き込み double。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

トレンドラインの方程式をチャート上に表示するかどうかを指定します（Rsquaredvalue と同じラベルに）。 読み取り/書き込み boolean。

**戻り値:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

トレンドラインの方程式をチャート上に表示するかどうかを指定します（Rsquaredvalue と同じラベルに）。 読み取り/書き込み boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

多項式トレンドラインの次数を指定します。他のトレンドラインタイプでは無視されます。 値は 2 から 6 の間である必要があります。 読み取り/書き込み byte。

**戻り値:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

多項式トレンドラインの次数を指定します。他のトレンドラインタイプでは無視されます。 値は 2 から 6 の間である必要があります。 読み取り/書き込み byte。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

移動平均トレンドラインの期間を指定します。他のトレンドラインバリアントでは無視されます。 値は 2 から 255 の間である必要があります。 読み取り/書き込み byte。

**戻り値:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

移動平均トレンドラインの期間を指定します。他のトレンドラインバリアントでは無視されます。 値は 2 から 255 の間である必要があります。 読み取り/書き込み byte。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

トレンドラインの決定係数(R^2)をチャート上に表示するかどうかを指定します（方程式と同じラベルに）。 読み取り/書き込み boolean。

**戻り値:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

トレンドラインの決定係数(R^2)をチャート上に表示するかどうかを指定します（方程式と同じラベルに）。 読み取り/書き込み boolean。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

このトレンドラインに関連付けられた凡例エントリを表します（読み取り専用 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)）。

**戻り値:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
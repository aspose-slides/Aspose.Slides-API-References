---
title: ErrorBarsFormat
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: チャート系列のエラーバーを表します。
type: docs
url: /ja/com.aspose.slides/errorbarsformat/
---
**継承:** 
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:** 
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

チャート系列のエラーバーを表します。ErrorBars のカスタム値は IChartDataPointCollection にあります ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティ内)。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | エラーバーのタイプを取得または設定します。 |
| [setType(int value)](#setType-int-) | エラーバーのタイプを取得または設定します。 |
| [getValueType()](#getValueType--) | エラーバーの長さを決定する可能な方法を表します。 |
| [setValueType(int value)](#setValueType-int-) | エラーバーの長さを決定する可能な方法を表します。 |
| [hasEndCap()](#hasEndCap--) | エラーバーにエンドキャップが描画されないことを指定します。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | エラーバーにエンドキャップが描画されないことを指定します。 |
| [getValue()](#getValue--) | Fixed、Percentage、StandardDeviation の値タイプでエラーバーの長さを決定するために使用される値を取得または設定します。 |
| [setValue(float value)](#setValue-float-) | Fixed、Percentage、StandardDeviation の値タイプでエラーバーの長さを決定するために使用される値を取得または設定します。 |
| [getFormat()](#getFormat--) | エラーバーの書式を表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | エラーバーの書式を表します。 |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [isVisible()](#isVisible--) | エラーバーの表示状態を取得または設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | エラーバーの表示状態を取得または設定します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### getType() {#getType--}
```
public final int getType()
```

エラーバーのタイプを取得または設定します。読み取り/書き込み [ErrorBarType](../../com.aspose.slides/errorbartype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

エラーバーのタイプを取得または設定します。読み取り/書き込み [ErrorBarType](../../com.aspose.slides/errorbartype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

エラーバーの長さを決定する可能な方法を表します。カスタム値タイプの場合は、Series の DataPoints コレクション内の特定データポイントの ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) プロパティを使用して値を指定します。Fixed、Percentage、StandardDeviation の値タイプの場合は Value プロパティを使用して値を指定します。読み取り/書き込み [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**戻り値:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

エラーバーの長さを決定する可能な方法を表します。カスタム値タイプの場合は、Series の DataPoints コレクション内の特定データポイントの ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) プロパティを使用して値を指定します。Fixed、Percentage、StandardDeviation の値タイプの場合は Value プロパティを使用して値を指定します。読み取り/書き込み [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

エラーバーにエンドキャップが描画されないことを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

エラーバーにエンドキャップが描画されないことを指定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Fixed、Percentage、StandardDeviation の値タイプでエラーバーの長さを決定するために使用される値を取得または設定します。その他の場合は NaN を返します。読み取り/書き込み float。

**戻り値:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Fixed、Percentage、StandardDeviation の値タイプでエラーバーの長さを決定するために使用される値を取得または設定します。その他の場合は NaN を返します。読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

エラーバーの書式を表します。読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

エラーバーの書式を表します。読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

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

エラーバーの表示状態を取得または設定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

エラーバーの表示状態を取得または設定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

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
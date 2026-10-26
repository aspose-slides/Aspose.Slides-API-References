---
title: IErrorBarsFormat
second_title: Aspose.Slides for Java API リファレンス
description: チャートシリーズのエラーバーを表します。
type: docs
url: /ja/com.aspose.slides/ierrorbarsformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

チャートシリーズのエラーバーを表します。ErrorBars のカスタム値は IChartDataPointCollection にあります ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティ)。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | エラーバーのタイプを取得または設定します。 |
| [setType(int value)](#setType-int-) | エラーバーのタイプを取得または設定します。 |
| [getValueType()](#getValueType--) | エラーバーの長さを決定する可能な方法を表します。 |
| [setValueType(int value)](#setValueType-int-) | エラーバーの長さを決定する可能な方法を表します。 |
| [hasEndCap()](#hasEndCap--) | エラーバーにエンドキャップが描画されないことを指定します。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | エラーバーにエンドキャップが描画されないことを指定します。 |
| [getValue()](#getValue--) | エラーバーの長さを決定するために Fixed、Percentage、StandardDeviation の値タイプで使用される値を取得または設定します。 |
| [setValue(float value)](#setValue-float-) | エラーバーの長さを決定するために Fixed、Percentage、StandardDeviation の値タイプで使用される値を取得または設定します。 |
| [getFormat()](#getFormat--) | エラーバーの書式を表します。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | エラーバーの書式を表します。 |
| [isVisible()](#isVisible--) | Error Bars の表示/非表示を取得または設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | Error Bars の表示/非表示を取得または設定します。 |

### getType() {#getType--}
```
public abstract int getType()
```

エラーバーのタイプを取得または設定します。読み取り/書き込み [ErrorBarType](../../com.aspose.slides/errorbartype)。

**戻り値:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

エラーバーのタイプを取得または設定します。読み取り/書き込み [ErrorBarType](../../com.aspose.slides/errorbartype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

エラーバーの長さを決定する可能な方法を表します。カスタム値タイプの場合、シリーズの DataPoints コレクション内の特定データポイントの [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティで値を指定します。読み取り/書き込み [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**戻り値:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

エラーバーの長さを決定する可能な方法を表します。カスタム値タイプの場合、シリーズの DataPoints コレクション内の特定データポイントの [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) プロパティで値を指定します。読み取り/書き込み [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

エラーバーにエンドキャップが描画されないことを指定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

エラーバーにエンドキャップが描画されないことを指定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Fixed、Percentage、StandardDeviation の値タイプで使用されるエラーバーの長さを決定する値を取得または設定します。読み取り/書き込み float。

**戻り値:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Fixed、Percentage、StandardDeviation の値タイプで使用されるエラーバーの長さを決定する値を取得または設定します。読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

エラーバーの書式を表します。読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

エラーバーの書式を表します。読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Error Bars の表示/非表示を取得または設定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Error Bars の表示/非表示を取得または設定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
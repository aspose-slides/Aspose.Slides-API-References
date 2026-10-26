---
title: ErrorBarsFormat
second_title: Aspose.Slides for Java API 參考
description: 代表圖表系列的誤差線。
type: docs
url: /zh-hant/com.aspose.slides/errorbarsformat/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

表示圖表系列的誤差線。ErrorBars 的自訂值位於 IChartDataPointCollection（在 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性中）。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 取得或設定誤差線的類型。 |
| [setType(int value)](#setType-int-) | 取得或設定誤差線的類型。 |
| [getValueType()](#getValueType--) | 表示可用來決定誤差線長度的可能方式。 |
| [setValueType(int value)](#setValueType-int-) | 表示可用來決定誤差線長度的可能方式。 |
| [hasEndCap()](#hasEndCap--) | 指定不在誤差線上繪製端帽。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 指定不在誤差線上繪製端帽。 |
| [getValue()](#getValue--) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 類型以決定誤差線長度的值。 |
| [setValue(float value)](#setValue-float-) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 類型以決定誤差線長度的值。 |
| [getFormat()](#getFormat--) | 表示誤差線的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示誤差線的格式。 |
| [getChart()](#getChart--) | 傳回父圖表。 |
| [isVisible()](#isVisible--) | 取得或設定 Error Bars 可見性。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 取得或設定 Error Bars 可見性。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 的父簡報。 |

### getType() {#getType--}
```
public final int getType()
```

取得或設定誤差線的類型。讀/寫 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**傳回：**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

取得或設定誤差線的類型。讀/寫 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

表示可用來決定誤差線長度的可能方式。若為自訂值類型，請使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性於系列的 DataPoints 集合中特定資料點以指定值。若為 Fixed、Percentage 或 StandardDeviation 類型，請使用 Value 屬性以指定值。讀/寫 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**傳回：**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

表示可用來決定誤差線長度的可能方式。若為自訂值類型，請使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性於系列的 DataPoints 集合中特定資料點以指定值。若為 Fixed、Percentage 或 StandardDeviation 類型，請使用 Value 屬性以指定值。讀/寫 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

指定不在誤差線上繪製端帽。讀/寫 boolean。

**傳回：**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

指定不在誤差線上繪製端帽。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

取得或設定用於 Fixed、Percentage 和 StandardDeviation 類型以決定誤差線長度的值。其他情況下將傳回 NaN。讀/寫 float。

**傳回：**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

取得或設定用於 Fixed、Percentage 和 StandardDeviation 類型以決定誤差線長度的值。其他情況下將傳回 NaN。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示誤差線的格式。讀/寫 [IFormat](../../com.aspose.slides/iformat)。

**傳回：**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示誤差線的格式。讀/寫 [IFormat](../../com.aspose.slides/iformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

傳回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**傳回：**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

取得或設定 Error Bars 可見性。讀/寫 boolean。

**傳回：**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

取得或設定 Error Bars 可見性。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回：**
[IPresentation](../../com.aspose.slides/ipresentation)
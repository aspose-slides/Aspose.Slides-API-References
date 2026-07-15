---
title: IErrorBarsFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表圖表系列的誤差棒。
type: docs
url: /zh-hant/com.aspose.slides/ierrorbarsformat/
---
**已實作的介面：**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

代表圖表系列的誤差棒。ErrorBars 的自訂值位於 IChartDataPointCollection（在 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 屬性中）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 取得或設定誤差棒的類型。 |
| [setType(int value)](#setType-int-) | 取得或設定誤差棒的類型。 |
| [getValueType()](#getValueType--) | 代表決定誤差棒長度的可能方式。 |
| [setValueType(int value)](#setValueType-int-) | 代表決定誤差棒長度的可能方式。 |
| [hasEndCap()](#hasEndCap--) | 指定不在誤差棒上繪製端帽。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 指定不在誤差棒上繪製端帽。 |
| [getValue()](#getValue--) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。 |
| [setValue(float value)](#setValue-float-) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。 |
| [getFormat()](#getFormat--) | 代表誤差棒的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 代表誤差棒的格式。 |
| [isVisible()](#isVisible--) | 取得或設定誤差棒的可見性。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 取得或設定誤差棒的可見性。 |
### getType() {#getType--}
```
public abstract int getType()
```

取得或設定誤差棒的類型。讀寫 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**返回值：**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

取得或設定誤差棒的類型。讀寫 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

代表決定誤差棒長度的可能方式。若為自訂值類型，請使用系列之 DataPoints 集合中特定資料點的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 屬性以指定值。讀寫 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**返回值：**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

代表決定誤差棒長度的可能方式。若為自訂值類型，請使用系列之 DataPoints 集合中特定資料點的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 屬性以指定值。讀寫 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

指定不在誤差棒上繪製端帽。讀寫 boolean。

**返回值：**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

指定不在誤差棒上繪製端帽。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。讀寫 float。

**返回值：**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。讀寫 float。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

代表誤差棒的格式。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**返回值：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

代表誤差棒的格式。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

取得或設定誤差棒的可見性。讀寫 boolean。

**返回值：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

取得或設定誤差棒的可見性。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
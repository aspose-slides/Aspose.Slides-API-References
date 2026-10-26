---
title: IErrorBarsFormat
second_title: Aspose.Slides for Java API 參考
description: 代表圖表系列的誤差棒。
type: docs
url: /zh-hant/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

代表圖表系列的誤差棒。ErrorBars 的自訂值位於 IChartDataPointCollection（位於 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 屬性）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 取得或設定誤差棒的類型。 |
| [setType(int value)](#setType-int-) | 取得或設定誤差棒的類型。 |
| [getValueType()](#getValueType--) | 表示決定誤差棒長度的可能方式。 |
| [setValueType(int value)](#setValueType-int-) | 表示決定誤差棒長度的可能方式。 |
| [hasEndCap()](#hasEndCap--) | 指定在誤差棒上不繪製端帽。 |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 指定在誤差棒上不繪製端帽。 |
| [getValue()](#getValue--) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。 |
| [setValue(float value)](#setValue-float-) | 取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。 |
| [getFormat()](#getFormat--) | 表示誤差棒的格式。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示誤差棒的格式。 |
| [isVisible()](#isVisible--) | 取得或設定 Error Bars 的可見性。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 取得或設定 Error Bars 的可見性。 |
### getType() {#getType--}
```
public abstract int getType()
```

取得或設定誤差棒的類型。可讀寫 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**傳回：**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

取得或設定誤差棒的類型。可讀寫 [ErrorBarType](../../com.aspose.slides/errorbartype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

表示決定誤差棒長度的可能方式。若為自訂值類型，請使用系列 DataPoints 集合中特定資料點的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 屬性。可讀寫 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**傳回：**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

表示決定誤差棒長度的可能方式。若為自訂值類型，請使用系列 DataPoints 集合中特定資料點的 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 屬性。可讀寫 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

指定在誤差棒上不繪製端帽。可讀寫 boolean。

**傳回：**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

指定在誤差棒上不繪製端帽。可讀寫 boolean。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。可讀寫 float。

**傳回：**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

取得或設定用於 Fixed、Percentage 和 StandardDeviation 值類型以決定誤差棒長度的值。可讀寫 float。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示誤差棒的格式。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**傳回：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示誤差棒的格式。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

取得或設定 Error Bars 的可見性。可讀寫 boolean。

**傳回：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

取得或設定 Error Bars 的可見性。可讀寫 boolean。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
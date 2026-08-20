---
title: ErrorBarsCustomValues
second_title: Aspose.Slides for Java API 參考
description: 指定誤差棒的值。
type: docs
url: /zh-hant/com.aspose.slides/errorbarscustomvalues/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

指定誤差棒的值。僅在 Error bars value type 為 Custom 時使用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 指定負向的誤差棒值。 |
| [getYMinus()](#getYMinus--) | 指定負向的誤差棒值。 |
| [getXPlus()](#getXPlus--) | 指定正向的誤差棒值。 |
| [getYPlus()](#getYPlus--) | 指定正向的誤差棒值。 |
### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```


指定負向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsXFormat，則可用。在其他情況下，此屬性會回傳 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```


指定負向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsYFormat，則可用。在其他情況下，此屬性會回傳 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```


指定正向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsXFormat，則可用。在其他情況下，此屬性會回傳 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```


指定正向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsYFormat，則可用。在其他情況下，此屬性會回傳 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
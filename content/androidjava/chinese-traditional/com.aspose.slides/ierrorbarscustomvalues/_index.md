---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API 參考
description: 指定誤差棒值。
type: docs
url: /zh-hant/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

指定誤差棒值。僅在 Error bars value type 為 Custom 時使用。
## Methods

| 方法 | 說明 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 指定負方向的誤差棒值。 |
| [getYMinus()](#getYMinus--) | 指定負方向的誤差棒值。 |
| [getXPlus()](#getXPlus--) | 指定正方向的誤差棒值。 |
| [getYPlus()](#getYPlus--) | 指定正方向的誤差棒值。 |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

指定負方向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsXFormat，則可用。否則此屬性返回 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

指定負方向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsYFormat，則可用。否則此屬性返回 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

指定正方向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsXFormat，則可用。否則此屬性返回 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

指定正方向的誤差棒值。若 error bars value type 為 Custom 且允許 ErrorBarsYFormat，則可用。否則此屬性返回 null。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: Specifies the errors bar values.
type: docs
url: /zh/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

指定误差棒值。仅在误差棒值类型为 Custom 时使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 指定负向误差棒值。 |
| [getYMinus()](#getYMinus--) | 指定负向误差棒值。 |
| [getXPlus()](#getXPlus--) | 指定正向误差棒值。 |
| [getYPlus()](#getYPlus--) | 指定正向误差棒值。 |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

指定负向误差棒值。如果误差棒值类型为 Custom 且允许 ErrorBarsXFormat，则可用。其他情况下此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

指定负向误差棒值。如果误差棒值类型为 Custom 且允许 ErrorBarsYFormat，则可用。其他情况下此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

指定正向误差棒值。如果误差棒值类型为 Custom 且允许 ErrorBarsXFormat，则可用。其他情况下此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

指定正向误差棒值。如果误差棒值类型为 Custom 且允许 ErrorBarsYFormat，则可用。其他情况下此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
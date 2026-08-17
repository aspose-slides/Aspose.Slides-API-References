---
title: ErrorBarsCustomValues
second_title: Aspose.Slides Java API 参考
description: 指定误差条的值。
type: docs
url: /zh/com.aspose.slides/errorbarscustomvalues/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)  
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

指定误差条的值。仅在误差条值类型为 Custom 时使用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 在负方向上指定误差条的值。 |
| [getYMinus()](#getYMinus--) | 在负方向上指定误差条的值。 |
| [getXPlus()](#getXPlus--) | 在正方向上指定误差条的值。 |
| [getYPlus()](#getYPlus--) | 在正方向上指定误差条的值。 |

### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```

在负方向上指定误差条的值。如果误差条值类型为 Custom 且允许 ErrorBarsXFormat，则此属性可用。在其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```

在负方向上指定误差条的值。如果误差条值类型为 Custom 且允许 ErrorBarsYFormat，则此属性可用。在其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```

在正方向上指定误差条的值。如果误差条值类型为 Custom 且允许 ErrorBarsXFormat，则此属性可用。在其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```

在正方向上指定误差条的值。如果误差条值类型为 Custom 且允许 ErrorBarsYFormat，则此属性可用。在其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
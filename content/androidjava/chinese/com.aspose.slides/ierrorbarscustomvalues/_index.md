---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: 指定误差条的值。
type: docs
url: /zh/com.aspose.slides/ierrorbarscustomvalues/
---
```
public interface IErrorBarsCustomValues
```

指定误差条的值。仅在 Error bars value type 为 Custom 时使用。
## 方法

| 方法 | 说明 |
| --- | --- |
| [getXMinus()](#getXMinus--) | 指定误差条在负方向的值。 |
| [getYMinus()](#getYMinus--) | 指定误差条在负方向的值。 |
| [getXPlus()](#getXPlus--) | 指定误差条在正方向的值。 |
| [getYPlus()](#getYPlus--) | 指定误差条在正方向的值。 |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

指定误差条在负方向的值。仅当 error bars value type 为 Custom 并且允许 ErrorBarsXFormat 时可用。任何其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

指定误差条在负方向的值。仅当 error bars value type 为 Custom 并且允许 ErrorBarsYFormat 时可用。任何其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

指定误差条在正方向的值。仅当 error bars value type 为 Custom 并且允许 ErrorBarsXFormat 时可用。任何其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

指定误差条在正方向的值。仅当 error bars value type 为 Custom 并且允许 ErrorBarsYFormat 时可用。任何其他情况下，此属性返回 null。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
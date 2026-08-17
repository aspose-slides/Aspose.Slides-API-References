---
title: IActualLayout
second_title: Aspose.Slides for Java API 参考
description: 指定图表元素的实际位置。
type: docs
url: /zh/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

指定图表元素的实际位置。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getActualX()](#getActualX--) | 指定图表元素相对于图表左上角的实际 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定图表元素相对于图表左上角的实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

指定图表元素相对于图表左上角的实际 x 位置（左）。调用方法 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

指定图表元素相对于图表左上角的实际顶部位置。调用方法 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

指定图表元素的实际宽度。调用方法 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

指定图表元素的实际高度。调用方法 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
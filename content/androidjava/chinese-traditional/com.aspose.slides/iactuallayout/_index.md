---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: 指定圖表元件的實際位置。
type: docs
url: /zh-hant/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

指定圖表元件的實際位置。
## Methods

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | 指定圖表元件相對於圖表左上角的實際 X 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元件相對於圖表左上角的實際上側位置。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元件的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元件的實際高度。 |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

指定圖表元件相對於圖表左上角的實際 X 位置（左）。在取得實際值之前，請先呼叫方法 IChart.ValidateChartLayout()。讀取 float。

**返回：**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

指定圖表元件相對於圖表左上角的實際上側位置。在取得實際值之前，請先呼叫方法 IChart.ValidateChartLayout()。讀取 float。

**返回：**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

指定圖表元件的實際寬度。在取得實際值之前，請先呼叫方法 IChart.ValidateChartLayout()。讀取 float。

**返回：**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

指定圖表元件的實際高度。在取得實際值之前，請先呼叫方法 IChart.ValidateChartLayout()。讀取 float。

**返回：**
float
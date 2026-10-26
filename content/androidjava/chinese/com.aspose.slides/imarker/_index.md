---
title: IMarker
second_title: Aspose.Slides for Android via Java API Reference
description: 表示图表的标记。
type: docs
url: /zh/com.aspose.slides/imarker/
---```
public interface IMarker
```

表示图表的标记。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSymbol()](#getSymbol--) | 表示线形图、散点图或雷达图中的标记样式。 |
| [setSymbol(int value)](#setSymbol-int-) | 表示线形图、散点图或雷达图中的标记样式。 |
| [getFormat()](#getFormat--) | 获取标记的填充。 |
| [getSize()](#getSize--) | 表示线形图、散点图或雷达图中的标记尺寸。 |
| [setSize(int value)](#setSize-int-) | 表示线形图、散点图或雷达图中的标记尺寸。 |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

表示线形图、散点图或雷达图中的标记样式。读/写 [MarkerStyleType](../../com.aspose.slides/markerstyletype)。

**返回:**  
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

表示线形图、散点图或雷达图中的标记样式。读/写 [MarkerStyleType](../../com.aspose.slides/markerstyletype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

获取标记的填充。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回:**  
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

表示线形图、散点图或雷达图中的标记尺寸。读/写 int。

**返回:**  
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

表示线形图、散点图或雷达图中的标记尺寸。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
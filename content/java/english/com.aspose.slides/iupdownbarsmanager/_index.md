---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
weight: 1090
url: /com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Provide access to up/down bars of Line- or Stock-chart.
## Methods

| Method | Description |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Returns format of the up bars. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Returns format of the down bars. |
| [hasUpDownBars()](#hasUpDownBars--) | Determines whether the chart has up/down bars. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Determines whether the chart has up/down bars. |
| [getGapWidth()](#getGapWidth--) | Returns or sets gap width. |
| [setGapWidth(int value)](#setGapWidth-int-) | Returns or sets gap width. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Returns format of the up bars. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Returns format of the down bars. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Determines whether the chart has up/down bars. Read/write boolean.

**Returns:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Determines whether the chart has up/down bars. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Returns or sets gap width. Read/write int.

**Returns:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Returns or sets gap width. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


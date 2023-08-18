---
title: IChartTitle
second_title: Aspose.Slides for Java API Reference
description: Represents chart title properties.
type: docs
weight: 708
url: /com.aspose.slides/icharttitle/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface IChartTitle extends ILayoutable, IOverridableText
```

Represents chart title properties.
## Methods

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap title. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap title. |
| [getFormat()](#getFormat--) | Returns the fill, line, effect styles of a title. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Determines whether other chart elements shall be allowed to overlap title. Read/write boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Determines whether other chart elements shall be allowed to overlap title. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returns the fill, line, effect styles of a title. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)

---
title: GradientStop
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a gradient format.
type: docs
weight: 226
url: /java/com.aspose.slides/gradientstop/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

Represents a gradient format.
## Constructors

| Constructor | Description |
| --- | --- |
| [GradientStop(IDOMObject parentImmediate)](#GradientStop-com.aspose.slides.IDOMObject-) |  |
| [GradientStop(IDOMObject parentImmediate, float position, System.Drawing.Color color)](#GradientStop-com.aspose.slides.IDOMObject-float-com.aspose.ms.System.Drawing.Color-) |  |
| [GradientStop(IDOMObject parentImmediate, float position, int presetColor)](#GradientStop-com.aspose.slides.IDOMObject-float-int-) |  |
| [GradientStop(IDOMObject parentImmediate, float position, int schemeColor, boolean cFix)](#GradientStop-com.aspose.slides.IDOMObject-float-int-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Returns or sets the position (0..1) of a gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets the position (0..1) of a gradient stop. |
| [getColor()](#getColor--) | Returns the color of a gradient stop. |
### GradientStop(IDOMObject parentImmediate) {#GradientStop-com.aspose.slides.IDOMObject-}
```
 GradientStop(IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### GradientStop(IDOMObject parentImmediate, float position, System.Drawing.Color color) {#GradientStop-com.aspose.slides.IDOMObject-float-com.aspose.ms.System.Drawing.Color-}
```
 GradientStop(IDOMObject parentImmediate, float position, System.Drawing.Color color)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| position | float |  |
| color | com.aspose.ms.System.Drawing.Color |  |

### GradientStop(IDOMObject parentImmediate, float position, int presetColor) {#GradientStop-com.aspose.slides.IDOMObject-float-int-}
```
 GradientStop(IDOMObject parentImmediate, float position, int presetColor)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| position | float |  |
| presetColor | int |  |

### GradientStop(IDOMObject parentImmediate, float position, int schemeColor, boolean cFix) {#GradientStop-com.aspose.slides.IDOMObject-float-int-boolean-}
```
 GradientStop(IDOMObject parentImmediate, float position, int schemeColor, boolean cFix)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| position | float |  |
| schemeColor | int |  |
| cFix | boolean |  |

### getPosition() {#getPosition--}
```
public final float getPosition()
```


Returns or sets the position (0..1) of a gradient stop. Read/write \`\`\` float \`\`\`.

**Returns:**
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```


Returns or sets the position (0..1) of a gradient stop. Read/write \`\`\` float \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Returns the color of a gradient stop. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)

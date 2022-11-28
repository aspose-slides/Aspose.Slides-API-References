---
title: IColorFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a color used in a presentation.
type: docs
weight: 713
url: /java/com.aspose.slides/icolorformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Represents a color used in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Returns or sets the color definition method. |
| [setColorType(int value)](#setColorType-int-) | Returns or sets the color definition method. |
| [getColor()](#getColor--) | Returns resulting color (with all color transformations applied). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Returns resulting color (with all color transformations applied). |
| [getPresetColor()](#getPresetColor--) | Returns or sets the color preset. |
| [setPresetColor(int value)](#setPresetColor-int-) | Returns or sets the color preset. |
| [getSystemColor()](#getSystemColor--) | Returns or sets the color identified by the system color table. |
| [setSystemColor(int value)](#setSystemColor-int-) | Returns or sets the color identified by the system color table. |
| [getSchemeColor()](#getSchemeColor--) | Returns or sets the color identified by a color scheme. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Returns or sets the color identified by a color scheme. |
| [getR()](#getR--) | Returns or sets the red component of a color. |
| [setR(byte value)](#setR-byte-) | Returns or sets the red component of a color. |
| [getG()](#getG--) | Returns or sets the green component of a color. |
| [setG(byte value)](#setG-byte-) | Returns or sets the green component of a color. |
| [getB()](#getB--) | Returns or sets the blue component of a color. |
| [setB(byte value)](#setB-byte-) | Returns or sets the blue component of a color. |
| [getFloatR()](#getFloatR--) | Returns or sets the red component of a color. |
| [setFloatR(float value)](#setFloatR-float-) | Returns or sets the red component of a color. |
| [getFloatG()](#getFloatG--) | Returns or sets the green component of a color. |
| [setFloatG(float value)](#setFloatG-float-) | Returns or sets the green component of a color. |
| [getFloatB()](#getFloatB--) | Returns or sets the blue component of a color. |
| [setFloatB(float value)](#setFloatB-float-) | Returns or sets the blue component of a color. |
| [getHue()](#getHue--) | Returns or sets the hue component of a color in HSL representation. |
| [setHue(float value)](#setHue-float-) | Returns or sets the hue component of a color in HSL representation. |
| [getSaturation()](#getSaturation--) | Returns or sets the saturation component of a color in HSL representation. |
| [setSaturation(float value)](#setSaturation-float-) | Returns or sets the saturation component of a color in HSL representation. |
| [getLuminance()](#getLuminance--) | Returns or sets the luminance component of a color in HSL representation. |
| [setLuminance(float value)](#setLuminance-float-) | Returns or sets the luminance component of a color in HSL representation. |
| [getColorTransform()](#getColorTransform--) | Returns the collection of color transformations applied to a color. |
| [toString(int format)](#toString-int-) | Returns a String that represents the current color format. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copy color format from "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Returns or sets the color definition method. Read/write [ColorType](../../com.aspose.slides/colortype).

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Returns or sets the color definition method. Read/write [ColorType](../../com.aspose.slides/colortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Returns resulting color (with all color transformations applied). Sets RGB colors and clears all color transformations. Read/write java.awt.Color.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Returns resulting color (with all color transformations applied). Sets RGB colors and clears all color transformations. Read/write java.awt.Color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Returns or sets the color preset. Read/write [PresetColor](../../com.aspose.slides/presetcolor).

**Returns:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Returns or sets the color preset. Read/write [PresetColor](../../com.aspose.slides/presetcolor).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Returns or sets the color identified by the system color table. Read/write [SystemColor](../../com.aspose.slides/systemcolor).

**Returns:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Returns or sets the color identified by the system color table. Read/write [SystemColor](../../com.aspose.slides/systemcolor).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Returns or sets the color identified by a color scheme. Read/write [SchemeColor](../../com.aspose.slides/schemecolor).

**Returns:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Returns or sets the color identified by a color scheme. Read/write [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```


Returns or sets the red component of a color. All color transformations are ignored. Read/write byte.

**Returns:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Returns or sets the red component of a color. All color transformations are ignored. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```


Returns or sets the green component of a color. All color transformations are ignored. Read/write byte.

**Returns:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Returns or sets the green component of a color. All color transformations are ignored. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```


Returns or sets the blue component of a color. All color transformations are ignored. Read/write byte.

**Returns:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Returns or sets the blue component of a color. All color transformations are ignored. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Returns or sets the red component of a color. All color transformations are ignored. Read/write float.

**Returns:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Returns or sets the red component of a color. All color transformations are ignored. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Returns or sets the green component of a color. All color transformations are ignored. Read/write float.

**Returns:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Returns or sets the green component of a color. All color transformations are ignored. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Returns or sets the blue component of a color. All color transformations are ignored. Read/write float.

**Returns:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Returns or sets the blue component of a color. All color transformations are ignored. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```


Returns or sets the hue component of a color in HSL representation. All color transformations are ignored. Read/write float.

**Returns:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Returns or sets the hue component of a color in HSL representation. All color transformations are ignored. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Returns or sets the saturation component of a color in HSL representation. All color transformations are ignored. Read/write float.

**Returns:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Returns or sets the saturation component of a color in HSL representation. All color transformations are ignored. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Returns or sets the luminance component of a color in HSL representation. All color transformations are ignored. Read/write float.

**Returns:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Returns or sets the luminance component of a color in HSL representation. All color transformations are ignored. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Returns the collection of color transformations applied to a color. Read-only [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Returns:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```


Returns a String that represents the current color format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | A type of color string format. |

**Returns:**
java.lang.String - A string that represents the current color format.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```


Copy color format from "color".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |


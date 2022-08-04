---
title: ColorChange
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a Color Change effect.
type: docs
weight: 106
url: /java/com.aspose.slides/colorchange/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorChange(IDOMObject parentImmediate)](#ColorChange-com.aspose.slides.IDOMObject-) | Color Change effect constructor. |
| [ColorChange(ColorFormat colorFrom, ColorFormat colorTo, boolean useAlpha, IDOMObject parentImmediate)](#ColorChange-com.aspose.slides.ColorFormat-com.aspose.slides.ColorFormat-boolean-com.aspose.slides.IDOMObject-) |  |
| [ColorChange(System.Drawing.Color colorFrom, System.Drawing.Color colorTo, boolean useAlpha, IDOMObject parentImmediate)](#ColorChange-com.aspose.ms.System.Drawing.Color-com.aspose.ms.System.Drawing.Color-boolean-com.aspose.slides.IDOMObject-) |  |
| [ColorChange(System.Drawing.Color colorFrom, int colorTo, boolean useAlpha, IDOMObject parentImmediate)](#ColorChange-com.aspose.ms.System.Drawing.Color-int-boolean-com.aspose.slides.IDOMObject-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color which will be replaced. |
| [getToColor()](#getToColor--) | Color which will replace. |
| [getEffective()](#getEffective--) | Gets effective Color Change effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [ColorChange](../../com.aspose.slides/colorchange) is equal to the current [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### ColorChange(IDOMObject parentImmediate) {#ColorChange-com.aspose.slides.IDOMObject-}
```
 ColorChange(IDOMObject parentImmediate)
```


Color Change effect constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### ColorChange(ColorFormat colorFrom, ColorFormat colorTo, boolean useAlpha, IDOMObject parentImmediate) {#ColorChange-com.aspose.slides.ColorFormat-com.aspose.slides.ColorFormat-boolean-com.aspose.slides.IDOMObject-}
```
 ColorChange(ColorFormat colorFrom, ColorFormat colorTo, boolean useAlpha, IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorFrom | [ColorFormat](../../com.aspose.slides/colorformat) |  |
| colorTo | [ColorFormat](../../com.aspose.slides/colorformat) |  |
| useAlpha | boolean |  |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### ColorChange(System.Drawing.Color colorFrom, System.Drawing.Color colorTo, boolean useAlpha, IDOMObject parentImmediate) {#ColorChange-com.aspose.ms.System.Drawing.Color-com.aspose.ms.System.Drawing.Color-boolean-com.aspose.slides.IDOMObject-}
```
 ColorChange(System.Drawing.Color colorFrom, System.Drawing.Color colorTo, boolean useAlpha, IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorFrom | com.aspose.ms.System.Drawing.Color |  |
| colorTo | com.aspose.ms.System.Drawing.Color |  |
| useAlpha | boolean |  |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### ColorChange(System.Drawing.Color colorFrom, int colorTo, boolean useAlpha, IDOMObject parentImmediate) {#ColorChange-com.aspose.ms.System.Drawing.Color-int-boolean-com.aspose.slides.IDOMObject-}
```
 ColorChange(System.Drawing.Color colorFrom, int colorTo, boolean useAlpha, IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorFrom | com.aspose.ms.System.Drawing.Color |  |
| colorTo | int |  |
| useAlpha | boolean |  |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Color which will be replaced. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Color which will replace. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Gets effective Color Change effect data with the inheritance applied.

**Returns:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [ColorChange](../../com.aspose.slides/colorchange) is equal to the current [ColorChange](../../com.aspose.slides/colorchange).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [ColorChange](../com.aspose.slides/colorchange) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.

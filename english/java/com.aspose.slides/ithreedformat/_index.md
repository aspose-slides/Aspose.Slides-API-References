---
title: IThreeDFormat
second_title: Aspose.Slides for Java API Reference
description:  Represents 3-D properties.
type: docs
weight: 1075
url: /java/com.aspose.slides/ithreedformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Represents 3-D properties.
## Methods

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Returns or sets the width of a 3D contour. |
| [setContourWidth(double value)](#setContourWidth-double-) | Returns or sets the width of a 3D contour. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returns or sets the height of an extrusion effect. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Returns or sets the height of an extrusion effect. |
| [getDepth()](#getDepth--) | Returns or sets the depth of a 3D shape. |
| [setDepth(double value)](#setDepth-double-) | Returns or sets the depth of a 3D shape. |
| [getBevelTop()](#getBevelTop--) | Returns or sets the type of a top 3D bevel. |
| [getBevelBottom()](#getBevelBottom--) | Returns or sets the type of a bottom 3D bevel. |
| [getContourColor()](#getContourColor--) | Returns or sets the color of a contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Returns or sets the color of an extrusion. |
| [getCamera()](#getCamera--) | Returns or sets the settings of a camera. |
| [getLightRig()](#getLightRig--) | Returns or sets the type of a light. |
| [getMaterial()](#getMaterial--) | Returns or sets the type of a material. |
| [setMaterial(int value)](#setMaterial-int-) | Returns or sets the type of a material. |
| [getEffective()](#getEffective--) | Gets effective 3-D formatting data with the inheritance applied. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Returns or sets the width of a 3D contour. Read/write double.

**Returns:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


Returns or sets the width of a 3D contour. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Returns or sets the height of an extrusion effect. Read/write double.

**Returns:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Returns or sets the height of an extrusion effect. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Returns or sets the depth of a 3D shape. Read/write double.

**Returns:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


Returns or sets the depth of a 3D shape. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


Returns or sets the type of a top 3D bevel. Read-only [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returns:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Returns or sets the type of a bottom 3D bevel. Read-only [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returns:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Returns or sets the color of a contour. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Returns or sets the color of an extrusion. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Returns or sets the settings of a camera. Read-only [ICamera](../../com.aspose.slides/icamera).

**Returns:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Returns or sets the type of a light. Read-only [ILightRig](../../com.aspose.slides/ilightrig).

**Returns:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Returns or sets the type of a material. Read/write [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returns:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Returns or sets the type of a material. Read/write [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Gets effective 3-D formatting data with the inheritance applied.

**Returns:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../com.aspose.slides/ithreedformateffectivedata).

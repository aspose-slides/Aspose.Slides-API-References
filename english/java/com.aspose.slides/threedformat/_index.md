---
title: ThreeDFormat
second_title: Aspose.Slides for Java API Reference
description:  Represents 3-D properties.
type: docs
weight: 569
url: /java/com.aspose.slides/threedformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
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
public final double getContourWidth()
```


Returns or sets the width of a 3D contour. Read/write double.

**Returns:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Returns or sets the width of a 3D contour. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Returns or sets the height of an extrusion effect. Read/write double.

**Returns:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Returns or sets the height of an extrusion effect. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```


Returns or sets the depth of a 3D shape. Read/write double.

**Returns:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Returns or sets the depth of a 3D shape. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Returns or sets the type of a top 3D bevel. Read-only [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returns:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Returns or sets the type of a bottom 3D bevel. Read-only [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returns:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Returns or sets the color of a contour. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Returns or sets the color of an extrusion. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Returns or sets the settings of a camera. Read-only [ICamera](../../com.aspose.slides/icamera).

**Returns:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Returns or sets the type of a light. Read-only [ILightRig](../../com.aspose.slides/ilightrig).

**Returns:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Returns or sets the type of a material. Read/write [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returns:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Returns or sets the type of a material. Read/write [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Gets effective 3-D formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates how to get effective properties for camera, light rig and shape's top bevel.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try 
>  {
>      IThreeDFormatEffectiveData threeDEffectiveData = pres.getSlides().get_Item(0).getShapes().get_Item(0).getThreeDFormat().getEffective();
>      System.out.println("= Effective camera properties =");
>      System.out.println("Type: " + threeDEffectiveData.getCamera().getCameraType());
>      System.out.println("Field of view: " + threeDEffectiveData.getCamera().getFieldOfViewAngle());
>      System.out.println("Zoom: " + threeDEffectiveData.getCamera().getZoom());
>      System.out.println("= Effective light rig properties =");
>      System.out.println("Type: " + threeDEffectiveData.getLightRig().getLightType());
>      System.out.println("Direction: " + threeDEffectiveData.getLightRig().getDirection());
>      System.out.println("= Effective shape's top face relief properties =");
>      System.out.println("Type: " + threeDEffectiveData.getBevelTop().getBevelType());
>      System.out.println("Width: " + threeDEffectiveData.getBevelTop().getWidth());
>      System.out.println("Height: " + threeDEffectiveData.getBevelTop().getHeight());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../com.aspose.slides/ithreedformateffectivedata).

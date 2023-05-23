---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which represents effective 3-D formatting properties.
type: docs
weight: 1082
url: /androidjava/com.aspose.slides/ithreedformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Immutable object which represents effective 3-D formatting properties.

--------------------

This interface is used together with the [IThreeDFormat](../../com.aspose.slides/ithreedformat) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Returns the width of a 3D contour. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returns the height of an extrusion effect. |
| [getDepth()](#getDepth--) | Returns the depth of a 3D shape. |
| [getBevelTop()](#getBevelTop--) | Returns the type of a top 3D bevel. |
| [getBevelBottom()](#getBevelBottom--) | Returns the type of a bottom 3D bevel. |
| [getContourColor()](#getContourColor--) | Returns the color of a contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Returns the color of an extrusion. |
| [getCamera()](#getCamera--) | Returns the settings of a camera. |
| [getLightRig()](#getLightRig--) | Returns the type of a light. |
| [getMaterial()](#getMaterial--) | Returns the type of a material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Returns the width of a 3D contour. Read-only double.

**Returns:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Returns the height of an extrusion effect. Read-only double.

**Returns:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Returns the depth of a 3D shape. Read-only double.

**Returns:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Returns the type of a top 3D bevel. Read-only [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Returns:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Returns the type of a bottom 3D bevel. Read-only [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Returns:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


Returns the color of a contour. Read-only java.lang.Integer.

**Returns:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


Returns the color of an extrusion. Read-only java.lang.Integer.

**Returns:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Returns the settings of a camera. Read-only [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Returns:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Returns the type of a light. Read-only [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Returns:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Returns the type of a material. Read-only [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returns:**
int

---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，表示有效的 3-D 格式属性。
type: docs
url: /zh/com.aspose.slides/ithreedformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

不可变对象，表示有效的 3-D 格式属性。

--------------------

此接口与 [IThreeDFormat](../../com.aspose.slides/ithreedformat) 接口一起使用，以返回应用继承后的有效格式值。

## 方法

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 返回 3D 轮廓的宽度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 返回挤压效果的高度。 |
| [getDepth()](#getDepth--) | 返回 3D 形状的深度。 |
| [getBevelTop()](#getBevelTop--) | 返回顶部 3D 倾斜的类型。 |
| [getBevelBottom()](#getBevelBottom--) | 返回底部 3D 倾斜的类型。 |
| [getContourColor()](#getContourColor--) | 返回轮廓的颜色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 返回挤压的颜色。 |
| [getCamera()](#getCamera--) | 返回相机的设置。 |
| [getLightRig()](#getLightRig--) | 返回灯光的类型。 |
| [getMaterial()](#getMaterial--) | 返回材料的类型。 |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

返回 3D 轮廓的宽度。只读 double。

**Returns:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

返回挤压效果的高度。只读 double。

**Returns:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

返回 3D 形状的深度。只读 double。

**Returns:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

返回顶部 3D 倾斜的类型。只读 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)。

**Returns:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

返回底部 3D 倾斜的类型。只读 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)。

**Returns:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

返回轮廓的颜色。只读 java.awt.Color。

**Returns:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

返回挤压的颜色。只读 java.awt.Color。

**Returns:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

返回相机的设置。只读 [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)。

**Returns:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

返回灯光的类型。只读 [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)。

**Returns:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

返回材料的类型。只读 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**Returns:**
int
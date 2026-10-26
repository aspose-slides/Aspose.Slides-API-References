---
title: IThreeDFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 3-D 属性。
type: docs
url: /zh/com.aspose.slides/ithreedformat/
---
**所有实现的接口：**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

表示 3-D 属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 返回或设置 3D 轮廓的宽度。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 返回或设置 3D 轮廓的宽度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 返回或设置 拉伸效果的高度。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 返回或设置 拉伸效果的高度。 |
| [getDepth()](#getDepth--) | 返回或设置 3D 形状的深度。 |
| [setDepth(double value)](#setDepth-double-) | 返回或设置 3D 形状的深度。 |
| [getBevelTop()](#getBevelTop--) | 返回或设置 顶部 3D 倾斜的类型。 |
| [getBevelBottom()](#getBevelBottom--) | 返回或设置 底部 3D 倾斜的类型。 |
| [getContourColor()](#getContourColor--) | 返回或设置 轮廓的颜色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 返回或设置 拉伸的颜色。 |
| [getCamera()](#getCamera--) | 返回或设置 相机的设置。 |
| [getLightRig()](#getLightRig--) | 返回或设置 光源的类型。 |
| [getMaterial()](#getMaterial--) | 返回或设置 材质的类型。 |
| [setMaterial(int value)](#setMaterial-int-) | 返回或设置 材质的类型。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 3-D 格式化数据。 |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

返回或设置 3D 轮廓的宽度。 可读写 double。

**返回：**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

返回或设置 3D 轮廓的宽度。 可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

返回或设置 拉伸效果的高度。 可读写 double。

**返回：**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

返回或设置 拉伸效果的高度。 可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

返回或设置 3D 形状的深度。 可读写 double。

**返回：**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

返回或设置 3D 形状的深度。 可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

返回或设置 顶部 3D 倾斜的类型。 只读 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

返回或设置 底部 3D 倾斜的类型。 只读 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

返回或设置 轮廓的颜色。 只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

返回或设置 拉伸的颜色。 只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

返回或设置 相机的设置。 只读 [ICamera](../../com.aspose.slides/icamera)。

**返回：**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

返回或设置 光源的类型。 只读 [ILightRig](../../com.aspose.slides/ilightrig)。

**返回：**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

返回或设置 材质的类型。 可读写 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**返回：**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

返回或设置 材质的类型。 可读写 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

获取应用继承后的有效 3-D 格式化数据。

**返回：**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
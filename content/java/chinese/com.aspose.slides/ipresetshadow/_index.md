---
title: IPresetShadow
second_title: Aspose.Slides Java API 参考
description: 表示预设阴影效果。
type: docs
url: /zh/com.aspose.slides/ippresetshadow/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

表示预设阴影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 阴影的方向。 |
| [setDirection(float value)](#setDirection-float-) | 阴影的方向。 |
| [getDistance()](#getDistance--) | 阴影的距离。 |
| [setDistance(double value)](#setDistance-double-) | 阴影的距离。 |
| [getShadowColor()](#getShadowColor--) | 阴影的颜色。 |
| [getPreset()](#getPreset--) | 预设。 |
| [setPreset(int value)](#setPreset-int-) | 预设。 |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

阴影的方向。读写 float.

**返回：**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

阴影的方向。读写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

阴影的距离。读写 double.

**返回：**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

阴影的距离。读写 double.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

阴影的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

预设。读写 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**返回：**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

预设。读写 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
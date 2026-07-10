---
title: IInnerShadow
second_title: Aspose.Slides Android Java API 参考
description: 表示内部阴影效果。
type: docs
url: /zh/com.aspose.slides/iinnershadow/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

表示内部阴影效果。

## 方法

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半径。 |
| [getDirection()](#getDirection--) | 阴影方向。 |
| [setDirection(float value)](#setDirection-float-) | 阴影方向。 |
| [getDistance()](#getDistance--) | 阴影距离。 |
| [setDistance(double value)](#setDistance-double-) | 阴影距离。 |
| [getShadowColor()](#getShadowColor--) | 阴影颜色。 |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

模糊半径。可读写 double。

**返回：**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

模糊半径。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

阴影方向。可读写 float。

**返回：**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

阴影方向。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

阴影距离。可读写 double。

**返回：**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

阴影距离。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

阴影颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
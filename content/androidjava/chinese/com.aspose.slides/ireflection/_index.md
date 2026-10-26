---
title: IReflection
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示反射效果。
type: docs
url: /zh/com.aspose.slides/ireflection/
---
**所有已实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

表示反射效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 指定起始 alpha 值（百分比）在 alpha 梯度斜坡上的起始位置。 |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 指定起始 alpha 值（百分比）在 alpha 梯度斜坡上的起始位置。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 指定结束 alpha 值（百分比）在 alpha 梯度斜坡上的结束位置。 |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 指定结束 alpha 值（百分比）在 alpha 梯度斜坡上的结束位置。 |
| [getFadeDirection()](#getFadeDirection--) | 指定反射的偏移方向。 |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 指定反射的偏移方向。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 起始反射不透明度。 |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 起始反射不透明度。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 结束反射不透明度。 |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 结束反射不透明度。 |
| [getBlurRadius()](#getBlurRadius--) | 模糊半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半径。 |
| [getDirection()](#getDirection--) | 反射方向。 |
| [setDirection(float value)](#setDirection-float-) | 反射方向。 |
| [getDistance()](#getDistance--) | 反射距离。 |
| [setDistance(double value)](#setDistance-double-) | 反射距离。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形对齐方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形对齐方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平倾斜角度。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 指定水平倾斜角度。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直倾斜角度。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 指定垂直倾斜角度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定在形状旋转时，反射是否随形状一起旋转。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指定在形状旋转时，反射是否随形状一起旋转。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平缩放因子，负值缩放会导致翻转。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 指定水平缩放因子，负值缩放会导致翻转。 |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直缩放因子，负值缩放会导致翻转。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 指定垂直缩放因子，负值缩放会导致翻转。 |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

指定起始 alpha 值（百分比）在 alpha 梯度斜坡上的起始位置。可读写 float。

**返回：**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

指定起始 alpha 值（百分比）在 alpha 梯度斜坡上的起始位置。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

指定结束 alpha 值（百分比）在 alpha 梯度斜坡上的结束位置。可读写 float。

**返回：**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

指定结束 alpha 值（百分比）在 alpha 梯度斜坡上的结束位置。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

指定反射的偏移方向。（角度）可读写 float。

**返回：**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

指定反射的偏移方向。（角度）可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

起始反射不透明度。（百分比）可读写 float。

**返回：**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

起始反射不透明度。（百分比）可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

结束反射不透明度。（百分比）可读写 float。

**返回：**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

结束反射不透明度。（百分比）可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

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

反射方向。可读写 float。

**返回：**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

反射方向。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

反射距离。可读写 double。

**返回：**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

反射距离。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形对齐方式。可读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**返回：**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形对齐方式。可读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

指定水平倾斜角度。可读写 double。

**返回：**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

指定水平倾斜角度。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

指定垂直倾斜角度。可读写 double。

**返回：**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

指定垂直倾斜角度。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

指定在形状旋转时，反射是否随形状一起旋转。可读写 boolean。

**返回：**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

指定在形状旋转时，反射是否随形状一起旋转。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

指定水平缩放因子，负值缩放会导致翻转。（百分比）可读写 double。

**返回：**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

指定水平缩放因子，负值缩放会导致翻转。（百分比）可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

指定垂直缩放因子，负值缩放会导致翻转。（百分比）可读写 double。

**返回：**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

指定垂直缩放因子，负值缩放会导致翻转。（百分比）可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
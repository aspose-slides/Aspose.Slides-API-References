---
title: IOuterShadow
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示外部阴影效果。
type: docs
url: /zh/com.aspose.slides/ioutershadow/
---
**所有已实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

表示外部阴影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半径（单位：点）。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半径（单位：点）。 |
| [getDirection()](#getDirection--) | 阴影方向（单位：度）。 |
| [setDirection(float value)](#setDirection-float-) | 阴影方向（单位：度）。 |
| [getDistance()](#getDistance--) | 阴影与对象的距离，单位为点。 |
| [setDistance(double value)](#setDistance-double-) | 阴影与对象的距离，单位为点。 |
| [getShadowColor()](#getShadowColor--) | 阴影颜色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形对齐方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形对齐方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平倾斜角度（单位：度）。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平倾斜角度（单位：度）。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直倾斜角度（单位：度）。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直倾斜角度（单位：度）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指示阴影是否随形状一起旋转。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指示阴影是否随形状一起旋转。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平缩放因子，以原始大小的百分比表示。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平缩放因子，以原始大小的百分比表示。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直缩放因子，以原始大小的百分比表示。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直缩放因子，以原始大小的百分比表示。 |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

模糊半径（单位：点）。默认值 - 0 pt。可读写 double。

**返回值：**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

模糊半径（单位：点）。默认值 - 0 pt。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

阴影方向（单位：度）。默认值 - 0 �（从左到右）。可读写 float。

**返回值：**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

阴影方向（单位：度）。默认值 - 0 �（从左到右）。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

阴影与对象的距离，单位为点。默认值 - 0 pt。可读写 double。

**返回值：**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

阴影与对象的距离，单位为点。默认值 - 0 pt。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

阴影颜色。默认值 - 自动黑（受主题影响）。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形对齐方式。默认值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**返回值：**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形对齐方式。默认值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

水平倾斜角度（单位：度）。默认值 - 0 �。可读写 double。

**返回值：**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

水平倾斜角度（单位：度）。默认值 - 0 �。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直倾斜角度（单位：度）。默认值 - 0 �。可读写 double。

**返回值：**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

垂直倾斜角度（单位：度）。默认值 - 0 �。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

指示阴影是否随形状一起旋转。默认值 - true。可读写 boolean。

**返回值：**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

指示阴影是否随形状一起旋转。默认值 - true。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

水平缩放因子，以原始大小的百分比表示。负值会导致翻转。默认值 - 100%。可读写 double。

**返回值：**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

水平缩放因子，以原始大小的百分比表示。负值会导致翻转。默认值 - 100%。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

垂直缩放因子，以原始大小的百分比表示。负值会导致翻转。默认值 - 100%。可读写 double。

**返回值：**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

垂直缩放因子，以原始大小的百分比表示。负值会导致翻转。默认值 - 100%。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
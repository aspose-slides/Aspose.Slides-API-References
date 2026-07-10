---
title: IReflectionEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 表示反射效果的不可变对象。
type: docs
url: /zh/com.aspose.slides/ireflectioneffectivedata/
---
**所有实现的接口:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

表示反射效果的不可变对象。
## 方法

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 梯度斜坡）。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 指定结束 alpha 值（百分比）的结束位置（沿 alpha 梯度斜坡）。 |
| [getFadeDirection()](#getFadeDirection--) | 指定偏移反射的方向。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 起始反射不透明度。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 结束反射不透明度。 |
| [getBlurRadius()](#getBlurRadius--) | 模糊半径。 |
| [getDirection()](#getDirection--) | 反射方向。 |
| [getDistance()](#getDistance--) | 反射距离。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形对齐方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平倾斜角度。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直倾斜角度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定在形状旋转时是否随形状一起旋转反射。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平缩放因子，负值缩放会导致翻转。 |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直缩放因子，负值缩放会导致翻转。 |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

指定起始 alpha 值（百分比）的起始位置（沿 alpha 梯度斜坡）。只读 float.

**返回:**
float

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

指定结束 alpha 值（百分比）的结束位置（沿 alpha 梯度斜坡）。只读 float.

**返回:**
float

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

指定偏移反射的方向。（角度）只读 float.

**返回:**
float

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

起始反射不透明度。（百分比）只读 float.

**返回:**
float

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

结束反射不透明度。（百分比）只读 float.

**返回:**
float

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

模糊半径。只读 double.

**返回:**
double

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

反射方向。只读 float.

**返回:**
float

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

反射距离。只读 double.

**返回:**
double

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形对齐方式。只读 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**返回:**
byte

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

指定水平倾斜角度。只读 double.

**返回:**
double

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

指定垂直倾斜角度。只读 double.

**返回:**
double

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

指定在形状旋转时是否随形状一起旋转反射。只读 boolean.

**返回:**
boolean

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

指定水平缩放因子，负值缩放会导致翻转。（百分比）只读 double.

**返回:**
double

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

指定垂直缩放因子，负值缩放会导致翻转。（百分比）只读 double.

**返回:**
double
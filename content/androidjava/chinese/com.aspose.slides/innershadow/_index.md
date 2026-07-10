---
title: InnerShadow
second_title: Aspose.Slides for Android via Java API 参考
description: 表示内部阴影效果。
type: docs
url: /zh/com.aspose.slides/innershadow/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示内部阴影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半径。 |
| [getDirection()](#getDirection--) | 阴影方向。 |
| [setDirection(float value)](#setDirection-float-) | 阴影方向。 |
| [getDistance()](#getDistance--) | 阴影距离。 |
| [setDistance(double value)](#setDistance-double-) | 阴影距离。 |
| [getShadowColor()](#getShadowColor--) | 阴影颜色。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效内部阴影效果数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的[InnerShadow](../../com.aspose.slides/innershadow)是否等于当前的[InnerShadow](../../com.aspose.slides/innershadow)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半径。可读写 double。

**返回：**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半径。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

阴影方向。可读写 float。

**返回：**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

阴影方向。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

阴影距离。可读写 double。

**返回：**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

阴影距离。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

阴影颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

获取应用继承后的有效内部阴影效果数据。

**返回：**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - 一个 [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。只读 long。

**返回：**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父级 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的[InnerShadow](../../com.aspose.slides/innershadow)是否等于当前的[InnerShadow](../../com.aspose.slides/innershadow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的[InnerShadow](../../com.aspose.slides/innershadow)。 |

**返回：**
boolean - 如果对象相等则返回 true；否则返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。
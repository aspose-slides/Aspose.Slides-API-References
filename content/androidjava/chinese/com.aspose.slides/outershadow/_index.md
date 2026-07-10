---
title: OuterShadow
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示外部阴影效果。
type: docs
url: /zh/com.aspose.slides/outershadow/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示外部阴影效果。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半径，单位为点。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半径，单位为点。 |
| [getDirection()](#getDirection--) | 阴影方向，单位为度。 |
| [setDirection(float value)](#setDirection-float-) | 阴影方向，单位为度。 |
| [getDistance()](#getDistance--) | 阴影与对象的距离，单位为点。 |
| [setDistance(double value)](#setDistance-double-) | 阴影与对象的距离，单位为点。 |
| [getShadowColor()](#getShadowColor--) | 阴影的颜色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形对齐方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形对齐方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平倾斜角度，单位为度。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平倾斜角度，单位为度。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直倾斜角度，单位为度。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直倾斜角度，单位为度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指示阴影是否随形状一起旋转。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指示阴影是否随形状一起旋转。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平缩放系数，以原始大小的百分比表示。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平缩放系数，以原始大小的百分比表示。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直缩放系数，以原始大小的百分比表示。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直缩放系数，以原始大小的百分比表示。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效外部阴影效果数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [OuterShadow](../../com.aspose.slides/outershadow) 是否等于当前的 [OuterShadow](../../com.aspose.slides/outershadow)。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数。 |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半径，单位为点。默认值 - 0 pt。读写 double。

**返回：**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半径，单位为点。默认值 - 0 pt。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

阴影方向，单位为度。默认值 - 0 � (left-to-right)。读写 float。

**返回：**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

阴影方向，单位为度。默认值 - 0 � (left-to-right)。读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

阴影与对象的距离，单位为点。默认值 - 0 pt。读写 double。

**返回：**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

阴影与对象的距离，单位为点。默认值 - 0 pt。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

阴影的颜色。默认值 - 自动黑色（主题依赖）。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

矩形对齐方式。默认值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**返回：**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

矩形对齐方式。默认值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

水平倾斜角度，单位为度。默认值 - 0 �。读写 double。

**返回：**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

水平倾斜角度，单位为度。默认值 - 0 �。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

垂直倾斜角度，单位为度。默认值 - 0 �。读写 double。

**返回：**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

垂直倾斜角度，单位为度。默认值 - 0 �。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

指示阴影是否随形状一起旋转。默认值 - true。读写 boolean。

**返回：**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

指示阴影是否随形状一起旋转。默认值 - true。读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

水平缩放系数，以原始大小的百分比表示。负数缩放会导致翻转。默认值 - 100%。读写 double。

**返回：**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

水平缩放系数，以原始大小的百分比表示。负数缩放会导致翻转。默认值 - 100%。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

垂直缩放系数，以原始大小的百分比表示。负数缩放会导致翻转。默认值 - 100%。读写 double。

**返回：**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

垂直缩放系数，以原始大小的百分比表示。负数缩放会导致翻转。默认值 - 100%。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

获取应用继承后的有效外部阴影效果数据。

**返回：**  
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - 一个 [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)。

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

确定指定的 [OuterShadow](../../com.aspose.slides/outershadow) 是否等于当前的 [OuterShadow](../../com.aspose.slides/outershadow)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [OuterShadow](../../com.aspose.slides/outershadow)。 |

**返回：**  
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数。

**返回：**  
int - 当前对象的哈希码。
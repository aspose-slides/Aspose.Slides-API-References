---
title: Reflection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示反射效果。
type: docs
url: /zh/com.aspose.slides/reflection/
---
**继承:**  
java.lang.Object  

**所有已实现的接口:**  
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示反射效果。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 指定起始 alpha 值（百分比）在 alpha 梯度坡道上的起始位置。 |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 指定起始 alpha 值（百分比）在 alpha 梯度坡道上的起始位置。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 指定结束 alpha 值（百分比）在 alpha 梯度坡道上的结束位置。 |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 指定结束 alpha 值（百分比）在 alpha 梯度坡道上的结束位置。 |
| [getFadeDirection()](#getFadeDirection--) | 指定偏移反射的方向。 |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 指定偏移反射的方向。 |
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
| [getRectangleAlign()](#getRectangleAlign--) | 矩形对齐。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形对齐。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平倾斜角度。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 指定水平倾斜角度。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直倾斜角度。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 指定垂直倾斜角度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定在形状旋转时，反射是否随形状一起旋转。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指定在形状旋转时，反射是否随形状一起旋转。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平缩放因子，负的缩放会导致翻转。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 指定水平缩放因子，负的缩放会导致翻转。 |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直缩放因子，负的缩放会导致翻转。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 指定垂直缩放因子，负的缩放会导致翻转。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效反射效果数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判断指定的 [Reflection](../../com.aspose.slides/reflection) 是否等于当前的 [Reflection](../../com.aspose.slides/reflection)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

指定起始 alpha 值（百分比）在 alpha 梯度坡道上的起始位置。读写 float。

**返回：**  
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

指定起始 alpha 值（百分比）在 alpha 梯度坡道上的起始位置。读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

指定结束 alpha 值（百分比）在 alpha 梯度坡道上的结束位置。读写 float。

**返回：**  
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

指定结束 alpha 值（百分比）在 alpha 梯度坡道上的结束位置。读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

指定偏移反射的方向。（角度）读写 float。

**返回：**  
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

指定偏移反射的方向。（角度）读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

起始反射不透明度。（百分比）读写 float。

**返回：**  
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

起始反射不透明度。（百分比）读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

结束反射不透明度。（百分比）读写 float。

**返回：**  
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

结束反射不透明度。（百分比）读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半径。读写 double。

**返回：**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半径。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

反射方向。读写 float。

**返回：**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

反射方向。读写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

反射距离。读写 double。

**返回：**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

反射距离。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

矩形对齐。读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**返回：**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

矩形对齐。读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

指定水平倾斜角度。读写 double。

**返回：**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

指定水平倾斜角度。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

指定垂直倾斜角度。读写 double。

**返回：**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

指定垂直倾斜角度。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

指定在形状旋转时，反射是否随形状一起旋转。读写 boolean。

**返回：**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

指定在形状旋转时，反射是否随形状一起旋转。读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

指定水平缩放因子，负的缩放会导致翻转。（百分比）读写 double。

**返回：**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

指定水平缩放因子，负的缩放会导致翻转。（百分比）读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

指定垂直缩放因子，负的缩放会导致翻转。（百分比）读写 double。

**返回：**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

指定垂直缩放因子，负的缩放会导致翻转。（百分比）读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

获取应用继承后的有效反射效果数据。

**返回：**  
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

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

判断指定的 [Reflection](../../com.aspose.slides/reflection) 是否等于当前的 [Reflection](../../com.aspose.slides/reflection)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [Reflection](../../com.aspose.slides/reflection)。 |

**返回：**  
boolean - 若对象相等返回 true；否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回：**  
int - 当前对象的哈希码。
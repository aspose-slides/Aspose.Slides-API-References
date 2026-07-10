---
title: Glow
second_title: Aspose.Slides Android 版通过 Java API 参考
description: 表示一种 Glow 效果，在对象的边缘外添加彩色模糊轮廓。
type: docs
url: /zh/com.aspose.slides/glow/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示一种 Glow 效果，在对象的边缘外添加彩色模糊轮廓。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
| [getEffective()](#getEffective--) | Gets effective Glow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Glow](../../com.aspose.slides/glow) is equal to the current [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

Radius. 读取/写入 double .

**返回值:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Radius. 读取/写入 double .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Color format. 只读 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

获取应用继承后的有效 Glow 效果数据。

**返回值:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version。只读 long。

**返回值:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回值:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [Glow](../../com.aspose.slides/glow) 是否等于当前的 [Glow](../../com.aspose.slides/glow)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | The [Glow](../../com.aspose.slides/glow) to compare. |

**返回值:**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回值:**
int - A hash code for the current object.
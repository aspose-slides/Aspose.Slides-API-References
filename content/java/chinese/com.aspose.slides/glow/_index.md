---
title: Glow
second_title: Aspose.Slides for Java API 参考
description: 表示一种 Glow 效果，其中在对象的边缘之外添加了颜色模糊的轮廓。
type: docs
url: /zh/com.aspose.slides/glow/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示一种 Glow 效果，其中在对象的边缘之外添加了颜色模糊的轮廓。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 半径。 |
| [setRadius(double value)](#setRadius-double-) | 半径。 |
| [getColor()](#getColor--) | 颜色格式。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 Glow 效果数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [Glow](../../com.aspose.slides/glow) 是否等于当前的 [Glow](../../com.aspose.slides/glow)。 |
| [hashCode()](#hashCode--) | 用作特定类型的哈希函数。 |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

半径。读写 double 。

**返回：**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

半径。读写 double 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

获取应用继承后的有效 Glow 效果数据。

**返回：**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - 一个 [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)。
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

确定指定的 [Glow](../../com.aspose.slides/glow) 是否等于当前的 [Glow](../../com.aspose.slides/glow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [Glow](../../com.aspose.slides/glow)。 |

**返回：**
boolean - 如果对象相等则返回 true；否则返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

用作特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。
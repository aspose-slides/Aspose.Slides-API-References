---
title: SoftEdge
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种柔和边缘效果。
type: docs
url: /zh/com.aspose.slides/softedge/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示一种柔和边缘效果。形状的边缘被模糊，而填充不受影响。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 指定要应用于边缘的模糊半径。 |
| [setRadius(double value)](#setRadius-double-) | 指定要应用于边缘的模糊半径。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效 Soft Edge 效果数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [SoftEdge](../../com.aspose.slides/softedge) 是否等于当前的 [SoftEdge](../../com.aspose.slides/softedge)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

指定要应用于边缘的模糊半径。读/写 double.

**返回:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

指定要应用于边缘的模糊半径。读/写 double.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

获取已应用继承的有效 Soft Edge 效果数据。

**返回:**  
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。只读 long。

**返回:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父级 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [SoftEdge](../../com.aspose.slides/softedge) 是否等于当前的 [SoftEdge](../../com.aspose.slides/softedge)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [SoftEdge](../../com.aspose.slides/softedge)。 |

**返回:**  
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回:**  
int - 当前对象的哈希码。
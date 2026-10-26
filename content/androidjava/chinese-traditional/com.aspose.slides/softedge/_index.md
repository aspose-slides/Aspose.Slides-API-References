---
title: SoftEdge
second_title: Aspose.Slides for Android via Java API 參考
description: 代表軟邊緣效果。
type: docs
url: /zh-hant/com.aspose.slides/softedge/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

代表軟邊緣效果。形狀的邊緣被模糊，而填充不受影響。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 指定要套用於邊緣的模糊半徑。 |
| [setRadius(double value)](#setRadius-double-) | 指定要套用於邊緣的模糊半徑。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Soft Edge 效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [SoftEdge](../../com.aspose.slides/softedge) 是否等於目前的 [SoftEdge](../../com.aspose.slides/softedge)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

指定要套用於邊緣的模糊半徑。讀寫 double.

**返回:**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

指定要套用於邊緣的模糊半徑。讀寫 double.

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

取得套用繼承後的有效 Soft Edge 效果資料。

**返回:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - 一個 [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**返回:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

傳回父級 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [SoftEdge](../../com.aspose.slides/softedge) 是否等於目前的 [SoftEdge](../../com.aspose.slides/softedge)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [SoftEdge](../../com.aspose.slides/softedge)。 |

**返回:**
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回:**
int - 目前物件的雜湊碼。
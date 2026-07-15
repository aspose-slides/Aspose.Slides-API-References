---
title: Glow
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一種 Glow 效果，會在物件的邊緣之外添加顏色模糊輪廓。
type: docs
url: /zh-hant/com.aspose.slides/glow/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示一個 Glow 效果，會在物件邊緣之外添加顏色模糊輪廓。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRadius()](#getRadius--) | 半徑。 |
| [setRadius(double value)](#setRadius-double-) | 半徑。 |
| [getColor()](#getColor--) | 顏色格式。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Glow 效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [Glow](../../com.aspose.slides/glow) 是否等於當前的 [Glow](../../com.aspose.slides/glow)。 |
| [hashCode()](#hashCode--) | 為特定類型提供雜湊函式。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

半徑。讀寫 double 。

**返回：**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

半徑。讀寫 double 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

顏色格式。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

取得套用繼承後的有效 Glow 效果資料。

**返回：**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**返回：**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回 parent IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [Glow](../../com.aspose.slides/glow) 是否等於當前的 [Glow](../../com.aspose.slides/glow)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [Glow](../../com.aspose.slides/glow)。 |

**返回：**
boolean - 如果物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

為特定類型提供雜湊函式。

**返回：**
int - 目前物件的雜湊碼。
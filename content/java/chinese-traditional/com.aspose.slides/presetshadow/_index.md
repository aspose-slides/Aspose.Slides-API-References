---
title: PresetShadow
second_title: Aspose.Slides for Java API 參考手冊
description: 表示一個預設陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/presetshadow/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示一個預設陰影效果。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 陰影的方向。 |
| [setDirection(float value)](#setDirection-float-) | 陰影的方向。 |
| [getDistance()](#getDistance--) | 陰影的距離。 |
| [setDistance(double value)](#setDistance-double-) | 陰影的距離。 |
| [getShadowColor()](#getShadowColor--) | 陰影的顏色。 |
| [getPreset()](#getPreset--) | 預設。 |
| [setPreset(int value)](#setPreset-int-) | 預設。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效預設陰影效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [PresetShadow](../../com.aspose.slides/presetshadow) 是否等於目前的 [PresetShadow](../../com.aspose.slides/presetshadow)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

陰影的方向。 可讀寫 float 。

**傳回：**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

陰影的方向。 可讀寫 float 。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

陰影的距離。 可讀寫 double 。

**傳回：**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

陰影的距離。 可讀寫 double 。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

陰影的顏色。 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

預設。 可讀寫 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**傳回：**
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

預設。 可讀寫 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

取得套用繼承後的有效預設陰影效果資料。

**傳回：**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - 一個 [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。 唯讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。 唯讀 long。

**傳回：**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

傳回父項 IPresentationComponent。 唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [PresetShadow](../../com.aspose.slides/presetshadow) 是否等於目前的 [PresetShadow](../../com.aspose.slides/presetshadow)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [PresetShadow](../../com.aspose.slides/presetshadow)。 |

**傳回：**
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回：**
int - 目前物件的雜湊碼。
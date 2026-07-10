---
title: PresetShadow
second_title: Aspose.Slides for Android via Java API 参考
description: 表示预设阴影效果。
type: docs
url: /zh/com.aspose.slides/presetshadow/
---
**Inheritance:**  
继承：

java.lang.Object

**All Implemented Interfaces:**  
所有实现的接口：  
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Represents a Preset Shadow effect.  
表示预设阴影效果。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | Direction of shadow. |
| [setDirection(float value)](#setDirection-float-) | Direction of shadow. |
| [getDistance()](#getDistance--) | Distance of shadow. |
| [setDistance(double value)](#setDistance-double-) | Distance of shadow. |
| [getShadowColor()](#getShadowColor--) | Color of shadow. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
| [getEffective()](#getEffective--) | Gets effective Preset Shadow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [PresetShadow](../../com.aspose.slides/presetshadow) is equal to the current [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

影子的方向。读/写 float 。

**返回：**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

影子的方向。读/写 float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

影子的距离。读/写 double 。

**返回：**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

影子的距离。读/写 double 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

影子的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

预设。读/写 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**返回：**  
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

预设。读/写 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

获取在应用继承后的有效预设阴影效果数据。

**返回：**  
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)。

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

确定指定的 [PresetShadow](../../com.aspose.slides/presetshadow) 是否等于当前的 [PresetShadow](../../com.aspose.slides/presetshadow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [PresetShadow](../../com.aspose.slides/presetshadow)。 |

**返回：**  
boolean - 如果对象相等返回 true；否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

为特定类型提供哈希函数。

**返回：**  
int - 当前对象的哈希码。
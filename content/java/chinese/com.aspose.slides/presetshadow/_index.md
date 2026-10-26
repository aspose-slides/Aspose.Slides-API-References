---
title: PresetShadow
second_title: Aspose.Slides for Java API 参考
description: 表示 Preset Shadow 效果。
type: docs
url: /zh/com.aspose.slides/presetshadow/
---
**继承:**
java.lang.Object

**已实现的接口:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示 Preset Shadow 效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 阴影的方向。 |
| [setDirection(float value)](#setDirection-float-) | 阴影的方向。 |
| [getDistance()](#getDistance--) | 阴影的距离。 |
| [setDistance(double value)](#setDistance-double-) | 阴影的距离。 |
| [getShadowColor()](#getShadowColor--) | 阴影的颜色。 |
| [getPreset()](#getPreset--) | Preset。 |
| [setPreset(int value)](#setPreset-int-) | Preset。 |
| [getEffective()](#getEffective--) | 获取在应用继承后有效的 Preset Shadow 效果数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [PresetShadow](../../com.aspose.slides/presetshadow) 是否等于当前的 [PresetShadow](../../com.aspose.slides/presetshadow)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


阴影的方向。读写  float .

**返回:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


阴影的方向。读写  float .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


阴影的距离。读写  double .

**返回:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


阴影的距离。读写  double .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


阴影的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Preset。读写 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**返回:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Preset。读写 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


获取在应用继承后有效的 Preset Shadow 效果数据。

**返回:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
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


确定指定的 [PresetShadow](../../com.aspose.slides/presetshadow) 是否等于当前的 [PresetShadow](../../com.aspose.slides/presetshadow)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [PresetShadow](../../com.aspose.slides/presetshadow)。 |

**返回:**
boolean - 如果对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


作为特定类型的哈希函数。

**返回:**
int - 当前对象的哈希码。
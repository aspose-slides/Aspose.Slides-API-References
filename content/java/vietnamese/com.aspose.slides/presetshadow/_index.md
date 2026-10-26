---
title: PresetShadow
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho hiệu ứng Bóng Đặt trước.
type: docs
url: /vi/com.aspose.slides/presetshadow/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Đại diện cho hiệu ứng Bóng Đã Đặt trước.

## Phương thức

| Phương thức | Mô tả |
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

Direction of shadow. Đọc/ghi  float .

**Trả về:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Direction of shadow. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Distance of shadow. Đọc/ghi  double .

**Trả về:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Distance of shadow. Đọc/ghi  double .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Color of shadow. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

Preset. Đọc/ghi [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Trả về:**
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Preset. Đọc/ghi [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Gets effective Preset Shadow effect data with the inheritance applied.

**Trả về:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Chỉ đọc long.

**Trả về:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Trả về IPresentationComponent cha. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determines whether the specified [PresetShadow](../../com.aspose.slides/presetshadow) is equal to the current [PresetShadow](../../com.aspose.slides/presetshadow).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | The [PresetShadow](../../com.aspose.slides/presetshadow) to compare. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Serves as a hash function for a particular type.

**Trả về:**
int - Mã băm cho đối tượng hiện tại.
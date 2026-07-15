---
title: PresetShadow
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hiệu ứng bóng Preset.
type: docs
url: /vi/com.aspose.slides/presetshadow/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Biểu diễn một hiệu ứng bóng Preset.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDirection()](#getDirection--) | Hướng của bóng. |
| [setDirection(float value)](#setDirection-float-) | Hướng của bóng. |
| [getDistance()](#getDistance--) | Khoảng cách của bóng. |
| [setDistance(double value)](#setDistance-double-) | Khoảng cách của bóng. |
| [getShadowColor()](#getShadowColor--) | Màu của bóng. |
| [getPreset()](#getPreset--) | Cài đặt sẵn. |
| [setPreset(int value)](#setPreset-int-) | Cài đặt sẵn. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng bóng Preset hiệu lực với tính kế thừa được áp dụng. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định liệu [PresetShadow](../../com.aspose.slides/presetshadow) được chỉ định có bằng với [PresetShadow](../../com.aspose.slides/presetshadow) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Hướng của bóng. Đọc/ghi  float .

**Trả về:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Hướng của bóng. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Khoảng cách của bóng. Đọc/ghi  double .

**Trả về:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Khoảng cách của bóng. Đọc/ghi  double .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Màu của bóng. Chỉ-đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Cài đặt sẵn. Đọc/ghi [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Trả về:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Cài đặt sẵn. Đọc/ghi [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng bóng Preset hiệu lực với tính kế thừa được áp dụng.

**Trả về:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - Một [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ-đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Phiên bản. Chỉ-đọc long.

**Trả về:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Trả về IPresentationComponent cha. Chỉ-đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định liệu [PresetShadow](../../com.aspose.slides/presetshadow) được chỉ định có bằng với [PresetShadow](../../com.aspose.slides/presetshadow) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; nếu không, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.
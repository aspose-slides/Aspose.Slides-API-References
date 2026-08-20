---
title: IPresetShadow
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho hiệu ứng bóng Preset.
type: docs
url: /vi/com.aspose.slides/ippresetshadow/
---
**Tất cả giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Đại diện cho hiệu ứng Preset Shadow.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDirection()](#getDirection--) | Hướng của bóng. |
| [setDirection(float value)](#setDirection-float-) | Hướng của bóng. |
| [getDistance()](#getDistance--) | Khoảng cách của bóng. |
| [setDistance(double value)](#setDistance-double-) | Khoảng cách của bóng. |
| [getShadowColor()](#getShadowColor--) | Màu của bóng. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Hướng của bóng. Đọc/ghi float.

**Trả về:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Hướng của bóng. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Khoảng cách của bóng. Đọc/ghi double.

**Trả về:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Khoảng cách của bóng. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Màu của bóng. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Preset. Đọc/ghi [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Trả về:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Preset. Đọc/ghi [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
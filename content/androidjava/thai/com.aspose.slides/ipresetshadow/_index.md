---
title: IPresetShadow
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟ็กต์เงาที่กำหนดไว้ล่วงหน้า.
type: docs
url: /th/com.aspose.slides/ipresetshadow/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

แสดงถึงเอฟเฟ็กต์เงาที่กำหนดไว้ล่วงหน้า.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDirection()](#getDirection--) | ทิศทางของเงา. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของเงา. |
| [getDistance()](#getDistance--) | ระยะของเงา. |
| [setDistance(double value)](#setDistance-double-) | ระยะของเงา. |
| [getShadowColor()](#getShadowColor--) | สีของเงา. |
| [getPreset()](#getPreset--) | พรีเซ็ต. |
| [setPreset(int value)](#setPreset-int-) | พรีเซ็ต. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


ทิศทางของเงา. อ่าน/เขียน float.

**คืนค่า:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


ทิศทางของเงา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


ระยะของเงา. อ่าน/เขียน double.

**คืนค่า:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


ระยะของเงา. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


สีของเงา. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


พรีเซ็ต. อ่าน/เขียน [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**คืนค่า:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


พรีเซ็ต. อ่าน/เขียน [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
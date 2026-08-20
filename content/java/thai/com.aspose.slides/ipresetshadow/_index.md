---
title: IPresetShadow
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงเอฟเฟกต์เงาที่กำหนดล่วงหน้า
type: docs
url: /th/com.aspose.slides/ipresetshadow/
---
**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

แสดงผลเงาที่กำหนดล่วงหน้า.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDirection()](#getDirection--) | ทิศทางของเงา. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของเงา. |
| [getDistance()](#getDistance--) | ระยะห่างของเงา. |
| [setDistance(double value)](#setDistance-double-) | ระยะห่างของเงา. |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

ระยะห่างของเงา. อ่าน/เขียน double.

**คืนค่า:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

ระยะห่างของเงา. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
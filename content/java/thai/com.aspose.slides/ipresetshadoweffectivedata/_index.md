---
title: IPresetShadowEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: วัตถุที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์เงาที่กำหนดล่วงหน้า.
type: docs
url: /th/com.aspose.slides/ippresetshadoweffectivedata/
---
**Interfaces ที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

วัตถุไม่เปลี่ยนแปลงที่แสดงถึงเอฟเฟกต์เงาที่กำหนดล่วงหน้า.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDirection()](#getDirection--) | ทิศทางของเงา. |
| [getDistance()](#getDistance--) | ระยะของเงา. |
| [getShadowColor()](#getShadowColor--) | สีของเงา. |
| [getPreset()](#getPreset--) | ค่าที่กำหนดล่วงหน้า. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

ทิศทางของเงา. อ่านได้เท่านั้น float.

**คืนค่า:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

ระยะของเงา. อ่านได้เท่านั้น double.

**คืนค่า:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

สีของเงา. อ่านได้เท่านั้น java.awt.Color.

**คืนค่า:**
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

ค่าที่กำหนดล่วงหน้า. อ่านได้เท่านั้น [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**คืนค่า:**
int
---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งแสดงคุณสมบัติการจัดรูปแบบ 3-D ที่มีประสิทธิภาพ.
type: docs
url: /th/com.aspose.slides/ithreedformateffectivedata/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งแสดงคุณสมบัติการจัดรูปแบบ 3-D ที่มีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IThreeDFormat](../../com.aspose.slides/ithreedformat) เพื่อคืนค่าการจัดรูปแบบที่มีประสิทธิภาพโดยมีการสืบทอดค่าแล้ว.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | คืนค่าความกว้างของคอนทัวร์ 3 มิติ. |
| [getExtrusionHeight()](#getExtrusionHeight--) | คืนค่าความสูงของเอฟเฟกต์การดันออก. |
| [getDepth()](#getDepth--) | คืนค่าความลึกของรูปทรง 3 มิติ. |
| [getBevelTop()](#getBevelTop--) | คืนค่าชนิดของบีเวลด้านบน 3 มิติ. |
| [getBevelBottom()](#getBevelBottom--) | คืนค่าชนิดของบีเวลด้านล่าง 3 มิติ. |
| [getContourColor()](#getContourColor--) | คืนค่าสีของคอนทัวร์. |
| [getExtrusionColor()](#getExtrusionColor--) | คืนค่าสีของการดันออก. |
| [getCamera()](#getCamera--) | คืนค่าการตั้งค่าของกล้อง. |
| [getLightRig()](#getLightRig--) | คืนค่าชนิดของแสง. |
| [getMaterial()](#getMaterial--) | คืนค่าชนิดของวัสดุ. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

คืนค่าความกว้างของคอนทัวร์ 3 มิติ. อ่านอย่างเดียว double.

**คืนค่า:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

คืนค่าความสูงของเอฟเฟกต์การดันออก. อ่านอย่างเดียว double.

**คืนค่า:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

คืนค่าความลึกของรูปทรง 3 มิติ. อ่านอย่างเดียว double.

**คืนค่า:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

คืนค่าชนิดของบีเวลด้านบน 3 มิติ. อ่านอย่างเดียว [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**คืนค่า:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

คืนค่าชนิดของบีเวลด้านล่าง 3 มิติ. อ่านอย่างเดียว [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**คืนค่า:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

คืนค่าสีของคอนทัวร์. อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

คืนค่าสีของการดันออก. อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

คืนค่าการตั้งค่าของกล้อง. อ่านอย่างเดียว [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**คืนค่า:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

คืนค่าชนิดของแสง. อ่านอย่างเดียว [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**คืนค่า:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

คืนค่าชนิดของวัสดุ. อ่านอย่างเดียว [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**คืนค่า:**
int
---
title: IThreeDFormatEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อ็อบเจ็กต์ไม่เปลี่ยนแปลงที่แสดงคุณสมบัติการจัดรูปแบบ 3-D ที่มีผล
type: docs
url: /th/com.aspose.slides/ithreedformateffectivedata/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

อ็อบเจ็กต์ไม่เปลี่ยนแปลงที่แสดงคุณสมบัติการจัดรูปแบบ 3-D ที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IThreeDFormat](../../com.aspose.slides/ithreedformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยมีการใช้การสืบทอด

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | คืนค่าความกว้างของคอนทัวร์ 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | คืนค่าสูงของเอฟเฟกต์การดึงออก. |
| [getDepth()](#getDepth--) | คืนค่าความลึกของรูปร่าง 3D. |
| [getBevelTop()](#getBevelTop--) | คืนค่าแบบของบีเวลด้านบน 3D. |
| [getBevelBottom()](#getBevelBottom--) | คืนค่าแบบของบีเวลด้านล่าง 3D. |
| [getContourColor()](#getContourColor--) | คืนค่าสีของคอนทัวร์. |
| [getExtrusionColor()](#getExtrusionColor--) | คืนค่าสีของการดึงออก. |
| [getCamera()](#getCamera--) | คืนค่าการตั้งค่าของกล้อง. |
| [getLightRig()](#getLightRig--) | คืนค่าแบบของแสง. |
| [getMaterial()](#getMaterial--) | คืนค่าแบบของวัสดุ. |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

คืนค่าความกว้างของคอนทัวร์ 3D. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

คืนค่าสูงของเอฟเฟกต์การดึงออก. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

คืนค่าความลึกของรูปร่าง 3D. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

คืนค่าแบบของบีเวลด้านบน 3D. อ่านอย่างเดียว [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**คืนค่า:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

คืนค่าแบบของบีเวลด้านล่าง 3D. อ่านอย่างเดียว [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**คืนค่า:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

คืนค่าสีของคอนทัวร์. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**
java.awt.Color

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

คืนค่าสีของการดึงออก. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**
java.awt.Color

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

คืนค่าแบบของแสง. อ่านอย่างเดียว [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**คืนค่า:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

คืนค่าแบบของวัสดุ. อ่านอย่างเดียว [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**คืนค่า:**
int
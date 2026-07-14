---
title: IThreeDFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคุณสมบัติ 3 มิติ.
type: docs
url: /th/com.aspose.slides/ithreedformat/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

แสดงคุณสมบัติ 3 มิติ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | คืนค่า หรือ กำหนดค่าความกว้างของคอนทัวร์ 3 มิติ. |
| [setContourWidth(double value)](#setContourWidth-double-) | คืนค่า หรือ กำหนดค่าความกว้างของคอนทัวร์ 3 มิติ. |
| [getExtrusionHeight()](#getExtrusionHeight--) | คืนค่า หรือ กำหนดค่าความสูงของเอฟเฟกต์เอ็กซ์ทรูชัน. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | คืนค่า หรือ กำหนดค่าความสูงของเอฟเฟกต์เอ็กซ์ทรูชัน. |
| [getDepth()](#getDepth--) | คืนค่า หรือ กำหนดค่าความลึกของรูปทรง 3 มิติ. |
| [setDepth(double value)](#setDepth-double-) | คืนค่า หรือ กำหนดค่าความลึกของรูปทรง 3 มิติ. |
| [getBevelTop()](#getBevelTop--) | คืนค่า หรือ กำหนดประเภทของบีเวลด้านบน 3 มิติ. |
| [getBevelBottom()](#getBevelBottom--) | คืนค่า หรือ กำหนดประเภทของบีเวลด้านล่าง 3 มิติ. |
| [getContourColor()](#getContourColor--) | คืนค่า หรือ กำหนดสีของคอนทัวร์. |
| [getExtrusionColor()](#getExtrusionColor--) | คืนค่า หรือ กำหนดสีของเอ็กซ์ทรูชัน. |
| [getCamera()](#getCamera--) | คืนค่า หรือ กำหนดการตั้งค่าของกล้อง. |
| [getLightRig()](#getLightRig--) | คืนค่า หรือ กำหนดประเภทของแสง. |
| [getMaterial()](#getMaterial--) | คืนค่า หรือ กำหนดประเภทของวัสดุ. |
| [setMaterial(int value)](#setMaterial-int-) | คืนค่า หรือ กำหนดประเภทของวัสดุ. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบ 3 มิติที่มีประสิทธิภาพ พร้อมการสืบทอดที่ใช้. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


คืนค่า หรือ กำหนดค่าความกว้างของคอนทัวร์ 3 มิติ. อ่าน/เขียน double.

**ค่าที่ส่งคืน:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


คืนค่า หรือ กำหนดค่าความกว้างของคอนทัวร์ 3 มิติ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


คืนค่า หรือ กำหนดค่าความสูงของเอฟเฟกต์เอ็กซ์ทรูชัน. อ่าน/เขียน double.

**ค่าที่ส่งคืน:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


คืนค่า หรือ กำหนดค่าความสูงของเอฟเฟกต์เอ็กซ์ทรูชัน. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


คืนค่า หรือ กำหนดค่าความลึกของรูปทรง 3 มิติ. อ่าน/เขียน double.

**ค่าที่ส่งคืน:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


คืนค่า หรือ กำหนดค่าความลึกของรูปทรง 3 มิติ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


คืนค่า หรือ กำหนดประเภทของบีเวลด้านบน 3 มิติ. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**ค่าที่ส่งคืน:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


คืนค่า หรือ กำหนดประเภทของบีเวลด้านล่าง 3 มิติ. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**ค่าที่ส่งคืน:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


คืนค่า หรือ กำหนดสีของคอนทัวร์. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ค่าที่ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


คืนค่า หรือ กำหนดสีของเอ็กซ์ทรูชัน. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ค่าที่ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


คืนค่า หรือ กำหนดการตั้งค่าของกล้อง. อ่านอย่างเดียว [ICamera](../../com.aspose.slides/icamera).

**ค่าที่ส่งคืน:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


คืนค่า หรือ กำหนดประเภทของแสง. อ่านอย่างเดียว [ILightRig](../../com.aspose.slides/ilightrig).

**ค่าที่ส่งคืน:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


คืนค่า หรือ กำหนดประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**ค่าที่ส่งคืน:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


คืนค่า หรือ กำหนดประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


ดึงข้อมูลการจัดรูปแบบ 3 มิติที่มีประสิทธิภาพ พร้อมการสืบทอดที่ใช้.

**ค่าที่ส่งคืน:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
---
title: IThreeDFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคุณสมบัติ 3-D.
type: docs
url: /th/com.aspose.slides/ithreedformat/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

แสดงคุณสมบัติ 3-D.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | คืนหรือกำหนดความกว้างของคอนทัวร์ 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | คืนหรือกำหนดความกว้างของคอนทัวร์ 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | คืนหรือกำหนดความสูงของเอฟเฟกต์การดันออก. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | คืนหรือกำหนดความสูงของเอฟเฟกต์การดันออก. |
| [getDepth()](#getDepth--) | คืนหรือกำหนดความลึกของรูปร่าง 3D. |
| [setDepth(double value)](#setDepth-double-) | คืนหรือกำหนดความลึกของรูปร่าง 3D. |
| [getBevelTop()](#getBevelTop--) | คืนหรือกำหนดประเภทของบีเวลด้านบน 3D. |
| [getBevelBottom()](#getBevelBottom--) | คืนหรือกำหนดประเภทของบีเวลด้านล่าง 3D. |
| [getContourColor()](#getContourColor--) | คืนหรือกำหนดสีของคอนทัวร์. |
| [getExtrusionColor()](#getExtrusionColor--) | คืนหรือกำหนดสีของการดันออก. |
| [getCamera()](#getCamera--) | คืนหรือกำหนดการตั้งค่าของกล้อง. |
| [getLightRig()](#getLightRig--) | คืนหรือกำหนดประเภทของแสง. |
| [getMaterial()](#getMaterial--) | คืนหรือกำหนดประเภทของวัสดุ. |
| [setMaterial(int value)](#setMaterial-int-) | คืนหรือกำหนดประเภทของวัสดุ. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการฟอร์แมต 3-D ที่มีผลพร้อมการสืบทอดที่นำไปใช้. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


คืนหรือกำหนดความกว้างของคอนทัวร์ 3D. อ่าน/เขียน double.

**คืนค่า:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


คืนหรือกำหนดความกว้างของคอนทัวร์ 3D. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


คืนหรือกำหนดความสูงของเอฟเฟกต์การดันออก. อ่าน/เขียน double.

**คืนค่า:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


คืนหรือกำหนดความสูงของเอฟเฟกต์การดันออก. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


คืนหรือกำหนดความลึกของรูปร่าง 3D. อ่าน/เขียน double.

**คืนค่า:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


คืนหรือกำหนดความลึกของรูปร่าง 3D. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


คืนหรือกำหนดประเภทของบีเวลด้านบน 3D. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**คืนค่า:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


คืนหรือกำหนดประเภทของบีเวลด้านล่าง 3D. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**คืนค่า:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


คืนหรือกำหนดสีของคอนทัวร์. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


คืนหรือกำหนดสีของการดันออก. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


คืนหรือกำหนดการตั้งค่าของกล้อง. อ่านอย่างเดียว [ICamera](../../com.aspose.slides/icamera).

**คืนค่า:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


คืนหรือกำหนดประเภทของแสง. อ่านอย่างเดียว [ILightRig](../../com.aspose.slides/ilightrig).

**คืนค่า:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


คืนหรือกำหนดประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**คืนค่า:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


คืนหรือกำหนดประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


ดึงข้อมูลการฟอร์แมต 3-D ที่มีผลพร้อมการสืบทอดที่นำไปใช้.

**คืนค่า:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
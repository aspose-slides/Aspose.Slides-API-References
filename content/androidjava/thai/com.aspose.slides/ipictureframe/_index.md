---
title: IPictureFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงกรอบที่มีรูปภาพอยู่ภายใน.
type: docs
url: /th/com.aspose.slides/ipictureframe/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

แทนภาพกรอบที่มีรูปภาพอยู่ภายใน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | คืนค่า locks ของ PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | คืนค่าอ็อบเจ็กต์ PictureFillFormat สำหรับกรอบรูป. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | คืนค่า หรือ ตั้งค่าสัดส่วนของความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | คืนค่า หรือ ตั้งค่าสัดส่วนของความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | คืนค่า หรือ ตั้งค่าสัดส่วนของความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | คืนค่า หรือ ตั้งค่าสัดส่วนของความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

คืนค่า locks ของ PictureFrame. อ่านอย่างเดียว [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**คืนค่า:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

คืนค่าอ็อบเจ็กต์ PictureFillFormat สำหรับกรอบรูป. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

คืนค่า หรือ ตั้งค่าสัดส่วนของความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. ค่า 1.0 แทน 100%. อ่าน/เขียน float.

**คืนค่า:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

คืนค่า หรือ ตั้งค่าสัดส่วนของความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. ค่า 1.0 แทน 100%. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

คืนค่า หรือ ตั้งค่าสัดส่วนของความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. ค่า 1.0 แทน 100%. อ่าน/เขียน float.

**คืนค่า:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

คืนค่า หรือ ตั้งค่าสัดส่วนของความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. ค่า 1.0 แทน 100%. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
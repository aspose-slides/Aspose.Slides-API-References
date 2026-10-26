---
title: IPictureFrame
second_title: Aspose.Slides สำหรับ Java API Reference
description: แทนกรอบที่มีรูปภาพภายใน.
type: docs
url: /th/com.aspose.slides/ipictureframe/
---
**อินเทอร์เฟซที่ทำทั้งหมด:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

แทนกรอบที่มีรูปภาพภายใน.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | คืนค่า PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | คืนค่าอ็อบเจกต์ PictureFillFormat สำหรับกรอบรูปภาพ. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | คืนค่า หรือ ตั้งค่าขนาดสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | คืนค่า หรือ ตั้งค่าขนาดสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | คืนค่า หรือ ตั้งค่าขนาดสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | คืนค่า หรือ ตั้งค่าขนาดสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


คืนค่า PictureFrame's locks. อ่านอย่างเดียว [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**คืนค่า:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


คืนค่าอ็อบเจกต์ PictureFillFormat สำหรับกรอบรูปภาพ. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


คืนค่า หรือ ตั้งค่าขนาดสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. ค่า 1.0 ตรงกับ 100%. อ่าน/เขียน float.

**คืนค่า:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


คืนค่า หรือ ตั้งค่าขนาดสเคลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. ค่า 1.0 ตรงกับ 100%. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


คืนค่า หรือ ตั้งค่าขนาดสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. ค่า 1.0 ตรงกับ 100%. อ่าน/เขียน float.

**คืนค่า:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


คืนค่า หรือ ตั้งค่าขนาดสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของกรอบรูปภาพ. ค่า 1.0 ตรงกับ 100%. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
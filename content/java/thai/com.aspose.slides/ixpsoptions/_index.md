---
title: IXpsOptions
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ XPS.
type: docs
url: /th/com.aspose.slides/ixpsoptions/
---
**อินเตอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ XPS
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True เพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True เพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True เพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**ผลลัพธ์:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True เพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**ผลลัพธ์:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. อ่าน/เขียน boolean.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
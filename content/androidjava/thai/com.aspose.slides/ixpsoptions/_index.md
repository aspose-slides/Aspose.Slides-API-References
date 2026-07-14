---
title: IXpsOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ XPS.
type: docs
url: /th/com.aspose.slides/ixpsoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in XPS format.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | ตั้งค่าเป็น True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอให้เป็นภาพ PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | ตั้งค่าเป็น True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอให้เป็นภาพ PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | ตั้งค่าเป็น True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | ตั้งค่าเป็น True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


ตั้งค่าเป็น True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอให้เป็นภาพ PNG. บูลีนแบบอ่าน/เขียน.

--------------------

ค่าเริ่มต้นคือ **true**.

**คืนค่า:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


ตั้งค่าเป็น True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอให้เป็นภาพ PNG. บูลีนแบบอ่าน/เขียน.

--------------------

ค่าเริ่มต้นคือ **true**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


ตั้งค่าเป็น True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. บูลีนแบบอ่าน/เขียน.

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


ตั้งค่าเป็น True เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. บูลีนแบบอ่าน/เขียน.

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
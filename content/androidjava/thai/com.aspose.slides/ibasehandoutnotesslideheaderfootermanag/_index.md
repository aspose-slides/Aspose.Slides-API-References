---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นผู้จัดการที่เป็นตัวแทนพฤติกรรมของตัวแทนพื้นที่รวมถึงตัวแทนพื้นที่ส่วนหัวสำหรับสไลด์ประเภท handout และ notes ทั้งหมด.
type: docs
url: /th/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

แสดงถึงผู้จัดการที่จัดพฤติกรรมของตัวแทนพื้นที่, รวมถึงตัวแทนพื้นที่ส่วนหัวสำหรับสไลด์ประเภท handout และ notes ทั้งหมด.

--------------------

ชื่ออินเทอร์เฟซต้นฉบับ "IBaseHandoutNotesSlideHeaderFooterManager" ถูกตัดให้เหลือ "IBaseHandoutNotesSlideHeaderFooterManag" เพื่อความเข้ากันได้กับ COM (ความยาวของชื่อประเภทต้องไม่เกิน 39).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | รับค่าที่บ่งชี้ว่ามีตัวแทนพื้นที่ส่วนหัวอยู่. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวแทนพื้นที่ส่วนหัวของสไลด์. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | ตั้งข้อความให้กับตัวแทนพื้นที่ส่วนหัวของสไลด์. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

รับค่าที่บ่งชี้ว่ามีตัวแทนพื้นที่ส่วนหัวอยู่. อ่านค่า boolean.

**คืนค่า:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวแทนพื้นที่ส่วนหัวของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวแทนพื้นที่ส่วนหัวปรากฏ, มิฉะนั้น - ซ่อนมัน. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

ตั้งข้อความให้กับตัวแทนพื้นที่ส่วนหัวของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |
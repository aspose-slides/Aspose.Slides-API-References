---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงผู้จัดการที่ถือพฤติกรรมของตำแหน่งเก็บข้อมูลชั่วคราว (placeholder) รวมถึงตำแหน่งหัวส่วนหัวสำหรับสไลด์ประเภท handout และ notes ทั้งหมด.
type: docs
url: /th/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

แสดงถึงผู้จัดการที่ถือพฤติกรรมของตำแหน่งเก็บข้อมูลชั่วคราว (placeholder) รวมถึงตำแหน่งหัวส่วนหัวสำหรับสไลด์ประเภท handout และ notes ทั้งหมด.

--------------------

ชื่ออินเทอร์เฟซต้นฉบับ "IBaseHandoutNotesSlideHeaderFooterManager" ถูกตัดให้เป็น "IBaseHandoutNotesSlideHeaderFooterManag" เพื่อความเข้ากันได้กับ COM (ความยาวของชื่อประเภทต้องไม่เกิน 39 ตัวอักษร).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | รับค่าที่บ่งชี้ว่ามีตำแหน่งหัวส่วนหัวอยู่. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | เปลี่ยนการมองเห็นตำแหน่งหัวส่วนหัวของสไลด์. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | ตั้งข้อความให้กับตำแหน่งหัวส่วนหัวของสไลด์. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


รับค่าที่บ่งชี้ว่ามีตำแหน่งหัวส่วนหัวอยู่. อ่านค่าแบบบูลีน.

**คืนค่า:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นตำแหน่งหัวส่วนหัวของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตำแหน่งหัวส่วนหัวปรากฏ, มิฉะนั้น - ซ่อนมัน. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


ตั้งข้อความให้กับตำแหน่งหัวส่วนหัวของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |
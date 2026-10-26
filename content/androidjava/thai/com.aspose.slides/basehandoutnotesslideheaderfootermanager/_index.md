---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงผู้จัดการที่ควบคุมพฤติกรรมของตัวแทนตัวยึด รวมถึงตัวแทนตัวยึดส่วนหัวสำหรับสไลด์ประเภท handout และ notes ทั้งหมด.
type: docs
url: /th/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**อินเทอร์เฟสที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

แสดงถึงผู้จัดการที่ควบคุมพฤติกรรมของตัวแทนตัวยึด รวมถึงตัวแทนตัวยึดส่วนหัวสำหรับสไลด์ประเภท handout และ notes ทั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | รับค่าที่บ่งชี้ว่ามีตัวแทนตัวยึดส่วนหัวอยู่. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวแทนตัวยึดส่วนหัวในสไลด์. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวแทนตัวยึดส่วนหัวของสไลด์. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


รับค่าที่บ่งชี้ว่ามีตัวแทนตัวยึดส่วนหัวอยู่. อ่านบูลีน.

**คืนค่า:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของตัวแทนตัวยึดส่วนหัวในสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวแทนตัวยึดส่วนหัวแสดง, false - ซ่อนมัน. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


ตั้งค่าข้อความให้กับตัวแทนตัวยึดส่วนหัวของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |
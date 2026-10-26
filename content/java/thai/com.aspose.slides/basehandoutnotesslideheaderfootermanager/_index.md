---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงถึงผู้จัดการที่เก็บพฤติกรรมของตัวยึดตำแหน่ง รวมถึงตัวยึดตำแหน่งหัวสำหรับสไลด์ชนิด handout และ notes ทั้งหมด.
type: docs
url: /th/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

แสดงถึงผู้จัดการที่เก็บพฤติกรรมของตัวยึดตำแหน่ง รวมถึงตัวยึดตำแหน่งหัวสำหรับสไลด์ชนิด handout และ notes ทั้งหมด.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | รับค่าที่บ่งบอกว่ามีตัวยึดตำแหน่งหัวอยู่. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดตำแหน่งหัวสไลด์. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวยึดตำแหน่งหัวสไลด์. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

รับค่าที่บ่งบอกว่ามีตัวยึดตำแหน่งหัวอยู่. อ่านแบบ boolean.

**คืนค่า:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดตำแหน่งหัวสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดตำแหน่งหัวเป็นที่มองเห็น, มิฉะนั้น - ซ่อนมัน. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

ตั้งค่าข้อความให้กับตัวยึดตำแหน่งหัวสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |
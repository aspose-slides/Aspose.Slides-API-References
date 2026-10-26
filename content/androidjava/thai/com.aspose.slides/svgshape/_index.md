---
title: SvgShape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงตัวเลือกสำหรับรูปร่าง SVG.
type: docs
url: /th/com.aspose.slides/svgshape/
---
**การสืบทอด:**
java.lang.Object

**ทั้งหมดที่ทำหน้าที่เป็น Interface:**
[com.aspose.slides.ISvgShape](../../com.aspose.slides/isvgshape)
```
public final class SvgShape implements ISvgShape
```

แสดงตัวเลือกสำหรับรูปร่าง SVG.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | ตั้งค่าผู้จัดการเหตุการณ์สำหรับรูปร่าง |
| [getId()](#getId--) | รับค่า ID ของรูปร่าง |
| [setId(String value)](#setId-java.lang.String-) | รับค่า ID ของรูปร่าง |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public final void setEventHandler(int eventType, String handler)
```

ตั้งค่าผู้จัดการเหตุการณ์สำหรับรูปร่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| eventType | int | ประเภทของเหตุการณ์ |
| handler | java.lang.String | ฟังก์ชัน Javascript เพื่อจัดการเหตุการณ์. ค่าที่เป็น Null จะลบผู้จัดการ |

### getId() {#getId--}
```
public final String getId()
```

รับค่า ID ของรูปร่าง

**ค่าที่คืนกลับ:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

รับค่า ID ของรูปร่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
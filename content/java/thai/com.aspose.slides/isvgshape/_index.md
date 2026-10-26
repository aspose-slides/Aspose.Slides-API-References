---
title: ISvgShape
second_title: Aspose.Slides for Java API Reference
description: เป็นตัวแทนของตัวเลือกสำหรับรูปแบบ SVG.
type: docs
url: /th/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

เป็นตัวแทนของตัวเลือกสำหรับรูปแบบ SVG.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | ตั้งค่าตัวจัดการเหตุการณ์สำหรับรูปร่าง |
| [getId()](#getId--) | ตั้งค่าหรือดึงค่า id สำหรับรูปร่าง |
| [setId(String value)](#setId-java.lang.String-) | ตั้งค่าหรือดึงค่า id สำหรับรูปร่าง |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

ตั้งค่าตัวจัดการเหตุการณ์สำหรับรูปร่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| eventType | int | ประเภทของเหตุการณ์. |
| handler | java.lang.String | ฟังก์ชัน Javascript เพื่อจัดการเหตุการณ์. ค่าที่เป็น Null จะลบตัวจัดการ. |

### getId() {#getId--}
```
public abstract String getId()
```

ตั้งค่าหรือดึงค่า id สำหรับรูปร่าง

**ผลลัพธ์:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

ตั้งค่าหรือดึงค่า id สำหรับรูปร่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options for SVG shape.
type: docs
url: /th/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

แสดงตัวเลือกสำหรับรูปทรง SVG.
## เมธอด

| Method | Description |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | กำหนดตัวจัดการเหตุการณ์สำหรับรูปร่าง |
| [getId()](#getId--) | กำหนดหรือรับค่า id สำหรับรูปร่าง |
| [setId(String value)](#setId-java.lang.String-) | กำหนดหรือรับค่า id สำหรับรูปร่าง |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


กำหนดตัวจัดการเหตุการณ์สำหรับรูปร่าง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | int | ประเภทของเหตุการณ์. |
| handler | java.lang.String | ฟังก์ชัน Javascript ที่จัดการเหตุการณ์. ค่าที่เป็น Null จะลบตัวจัดการ. |

### getId() {#getId--}
```
public abstract String getId()
```


กำหนดหรือรับค่า id สำหรับรูปร่าง

**คืนค่า:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


กำหนดหรือรับค่า id สำหรับรูปร่าง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
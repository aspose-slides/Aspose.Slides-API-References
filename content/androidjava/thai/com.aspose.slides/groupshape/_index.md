---
title: GroupShape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงกลุ่มของรูปร่างบนสไลด์.
type: docs
url: /th/com.aspose.slides/groupshape/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**อินเทอร์เฟซที่ทำตามทั้งหมด:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

แสดงถึงกลุ่มของรูปร่างบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง |
| [getGroupShapeLock()](#getGroupShapeLock--) | คืนค่าการล็อกของรูปร่าง |
| [getShapes()](#getShapes--) | คืนค่าชุดของรูปร่างภายในกลุ่ม |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: คืนค่า null สำหรับอ็อบเจ็กต์ GroupShape เนื่องจากไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**คืนค่า:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

คืนค่าชุดของรูปร่างภายในกลุ่ม อ่านอย่างเดียว [IShapeCollection](../../com.aspose.slides/ishapecollection).

**คืนค่า:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
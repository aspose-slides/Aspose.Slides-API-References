---
title: GroupShape
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงกลุ่มรูปทรงบนสไลด์
type: docs
url: /th/com.aspose.slides/groupshape/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**All Implemented Interfaces:**  
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)  
```
public class GroupShape extends Shape implements IGroupShape
```

แสดงถึงกลุ่มรูปทรงบนสไลด์หนึ่ง.
## เมธอด

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | ส่งคืนออบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรงหนึ่ง |
| [getGroupShapeLock()](#getGroupShapeLock--) | ส่งคืนการล็อกของรูปทรง |
| [getShapes()](#getShapes--) | ส่งคืนคอลเลกชันของรูปทรงภายในกลุ่ม |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

ส่งคืนออบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรงหนึ่ง Note: ส่งคืนค่า null สำหรับออบเจ็กต์ GroupShape เนื่องจากไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

ส่งคืนการล็อกของรูปทรง อ่านอย่างเดียว [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Returns:**  
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

ส่งคืนคอลเลกชันของรูปทรงภายในกลุ่ม อ่านอย่างเดียว [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returns:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)
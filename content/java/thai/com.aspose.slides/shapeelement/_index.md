---
title: ShapeElement
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงส่วนของรูปร่างที่มีเส้นขอบและคุณสมบัติการเติมสีเดียวกัน.
type: docs
url: /th/com.aspose.slides/shapeelement/
---
**Inheritance:**  
สืบทอด:  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)  
```
public class ShapeElement implements IShapeElement
```

แทนส่วนของรูปทรงที่มีลักษณะขอบและการเติมสีเดียวกัน.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParentShape()](#getParentShape--) | คืนค่า Shape_PPT ที่สร้างโดยอีลิเมนต์นี้. |
| [getPathPoints()](#getPathPoints--) | รับอาร์เรย์ของจุดที่กำหนดรูปทรงทางเรขาคณิตของเส้นทางของอีลิเมนต์. |
| [getPathTypes()](#getPathTypes--) | รับอาร์เรย์ของค่าไบท์ที่ระบุประเภทของแต่ละจุดในเส้นทางของอีลิเมนต์. |
| [getFillSource()](#getFillSource--) | คืนข้อมูลเกี่ยวกับวิธีการเติมอีลิเมนต์. |
| [getStrokeSource()](#getStrokeSource--) | คืนข้อมูลเกี่ยวกับวิธีการวาดเส้นขอบอีลิเมนต์. |

### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

คืนค่า Shape_PPT ที่สร้างโดยอีลิเมนต์นี้. อ่านได้อย่างเดียว [Shape](../../com.aspose.slides/shape).

**คืนค่า:**
[Shape](../../com.aspose.slides/shape)

### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

รับอาร์เรย์ของจุดที่กำหนดรูปทรงทางเรขาคณิตของเส้นทางของอีลิเมนต์.

**คืนค่า:**
java.awt.geom.Point2D.Float[]

### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

รับอาร์เรย์ของค่าไบท์ที่ระบุประเภทของแต่ละจุดในเส้นทางของอีลิเมนต์.

**0** ระบุว่าจุดเป็นจุดเริ่มต้นของรูปทรง.  
**1** ระบุว่าจุดเป็นหนึ่งในสองจุดสิ้นสุดของเส้น.  
**3** ระบุว่าจุดเป็นจุดสิ้นสุดหรือจุดควบคุมของเส้นโค้งเบซิเยอร์ระดับสาม.  
**7** ปิดบังบิตทั้งหมดยกเว้นบิตสามบิตล่างที่ระบุประเภทของจุด.  
**16** ระบุว่าเซกเมนต์ที่สอดคล้องเป็นเส้นประ.  
**32** ระบุว่าจุดเป็นเครื่องหมาย.  
**128** ระบุว่าจุดเป็นจุดสุดท้ายในเส้นทางย่อยที่ปิด (รูปทรง).  
**129** ระบุจุดข้อมูลที่เป็นทั้งจุดสิ้นสุดของเซกเมนต์เส้นและจุดสุดท้ายของเส้นทางย่อยที่ปิด.

**คืนค่า:**
byte[]

### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

คืนข้อมูลเกี่ยวกับวิธีการเติมอีลิเมนต์. อ่านได้อย่างเดียว [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**คืนค่า:**
byte

### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

คืนข้อมูลเกี่ยวกับวิธีการวาดเส้นขอบอีลิเมนต์. อ่านได้อย่างเดียว [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**คืนค่า:**
byte
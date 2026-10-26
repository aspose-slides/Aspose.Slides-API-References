---
title: ShapeElement
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แทนส่วนหนึ่งของรูปทรงที่มีคุณสมบัติของเส้นขอบและการเติมสีเดียวกัน
type: docs
url: /th/com.aspose.slides/shapeelement/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

แทนส่วนหนึ่งของรูปทรงที่มีคุณสมบัติของเส้นขอบและการเติมสีเดียวกัน
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParentShape()](#getParentShape--) | คืนค่า Shape_PPT ที่สร้างองค์ประกอบนี้ |
| [getPathPoints()](#getPathPoints--) | รับอาเรย์ของจุดที่กำหนดเรขาคณิตของเส้นทางขององค์ประกอบ |
| [getPathTypes()](#getPathTypes--) | รับอาเรย์ของค่า byte ที่ระบุประเภทของแต่ละจุดในเส้นทางขององค์ประกอบ |
| [getFillSource()](#getFillSource--) | คืนข้อมูลเกี่ยวกับวิธีการเติมสีให้กับองค์ประกอบ |
| [getStrokeSource()](#getStrokeSource--) | คืนข้อมูลเกี่ยวกับวิธีการวาดเส้นขอบให้กับองค์ประกอบ |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

คืนค่า Shape_PPT ที่สร้างองค์ประกอบนี้. อ่านอย่างเดียว [Shape](../../com.aspose.slides/shape).

**คืนค่า:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

รับอาเรย์ของจุดที่กำหนดเรขาคณิตของเส้นทางขององค์ประกอบ

**คืนค่า:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

รับอาเรย์ของค่า byte ที่ระบุประเภทของแต่ละจุดในเส้นทางขององค์ประกอบ

**0** บ่งบอกว่าจุดเป็นจุดเริ่มต้นของรูป

**1** บ่งบอกว่าจุดเป็นหนึ่งในสองจุดสิ้นสุดของเส้นตรง

**3** บ่งบอกว่าจุดเป็นจุดสิ้นสุดหรือจุดควบคุมของเส้นโค้งแบบ Bézier cubic

**7** ปิดบังบิตทั้งหมดที่ไม่ใช่สามบิตล่างสุด ซึ่งบ่งบอกประเภทของจุด

**16** ระบุว่าเซกเมนต์ที่เกี่ยวข้องเป็นเส้นประ

**32** ระบุว่าจุดเป็นเครื่องหมาย

**128** ระบุว่าจุดเป็นจุดสุดท้ายในเส้นทางย่อยที่ปิด (รูป)

**129** บ่งบอกว่าจุดข้อมูลเป็นทั้งจุดสิ้นสุดของเซกเมนต์เส้นและจุดสุดท้ายของเส้นทางย่อยที่ปิด

**คืนค่า:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

คืนข้อมูลเกี่ยวกับวิธีการเติมสีให้กับองค์ประกอบ. อ่านอย่างเดียว [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**คืนค่า:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

คืนข้อมูลเกี่ยวกับวิธีการวาดเส้นขอบให้กับองค์ประกอบ. อ่านอย่างเดียว [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**คืนค่า:**
byte
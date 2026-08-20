---
title: GeometryShape
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนคลาสแม่สำหรับรูปร่างเรขาคณิตทั้งหมด.
type: docs
url: /th/com.aspose.slides/geometryshape/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

อธิบายคลาสพ่อแม่สำหรับรูปร่างเรขาคณิตทั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ส่งคืนสำเนาของเส้นทางของรูปร่างเรขาคณิต |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | อัปเดตรูปทรงเรขาคณิตจากวัตถุ [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | อัปเดตรูปทรงเรขาคณิตจากอาร์เรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [getShapeStyle()](#getShapeStyle--) | ส่งคืนอ็อบเจกต์สไตล์ของรูปร่าง |
| [getShapeType()](#getShapeType--) | ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต |
| [setShapeType(int value)](#setShapeType-int-) | ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต |
| [getAdjustments()](#getAdjustments--) | ส่งคืนคอลเลกชันของค่าการปรับของรูปร่าง |
| [createShapeElements()](#createShapeElements--) | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปร่าง |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```


ส่งคืนสำเนาของเส้นทางของรูปร่างเรขาคณิต พิกัดอ้างอิงจากมุมบนซ้ายของรูปร่าง

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
com.aspose.slides.IGeometryPath[] - อาร์เรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```


อัปเดตรูปทรงเรขาคณิตจากวัตถุ [IGeometryPath](../../com.aspose.slides/igeometrypath) พิกัดต้องอ้างอิงจากมุมบนซ้ายของรูปร่าง การเปลี่ยนประเภทของรูปร่าง (ShapeType(#getShapeType.getShapeType/#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | เส้นทางเรขาคณิต |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```


อัปเดตรูปทรงเรขาคณิตจากอาร์เรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath) พิกัดต้องอ้างอิงจากมุมบนซ้ายของรูปร่าง การเปลี่ยนประเภทของรูปร่าง (ShapeType(#getShapeType.getShapeType/#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | อาร์เรย์ของเส้นทางเรขาคณิต |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```


ส่งคืนอ็อบเจกต์สไตล์ของรูปร่าง อ่านอย่างเดียว [IShapeStyle](../../com.aspose.slides/ishapestyle)

**ผลลัพธ์:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype)

**ผลลัพธ์:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```


ส่งคืนคอลเลกชันของค่าการปรับของรูปร่าง อ่านอย่างเดียว [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

**ผลลัพธ์:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```


สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปร่าง

**ผลลัพธ์:**
com.aspose.slides.IShapeElement[] - อาร์เรย์ของ [ShapeElement](../../com.aspose.slides/shapeelement)
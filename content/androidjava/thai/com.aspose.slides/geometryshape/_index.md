---
title: GeometryShape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
type: docs
url: /th/com.aspose.slides/geometryshape/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**ทุกอินเทอร์เฟซที่ทำการ Implement:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

เป็นคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิตนี้. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจกต์ [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | อัปเดตเรขาคณิตของรูปทรงจากอาเรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | ส่งคืนอ็อบเจกต์สไตล์ของรูปทรง. |
| [getShapeType()](#getShapeType--) | ส่งคืนหรือกำหนดประเภทของรูปแบบเรขาคณิตพรีเซ็ต. |
| [setShapeType(int value)](#setShapeType-int-) | ส่งคืนหรือกำหนดประเภทของรูปแบบเรขาคณิตพรีเซ็ต. |
| [getAdjustments()](#getAdjustments--) | ส่งคืนคอลเลกชันของค่าการปรับรูปทรง. |
| [createShapeElements()](#createShapeElements--) | สร้างและส่งคืนอาเรย์ขององค์ประกอบของรูปทรง. |

### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของรูปทรง.

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

**ส่งคืน:**  
com.aspose.slides.IGeometryPath[] - อาเรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath)

### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจกต์ [IGeometryPath](../../com.aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรง. เปลี่ยนประเภทของรูปทรง (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

อัปเดตเรขาคณิตของรูปทรงจากอาเรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรง. เปลี่ยนประเภทของรูปทรง (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | อาเรย์ของเส้นทางเรขาคณิต |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

ส่งคืนอ็อบเจกต์สไตล์ของรูปทรง. อ่านอย่างเดียว [IShapeStyle](../../com.aspose.slides/ishapestyle).

**ส่งคืน:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ส่งคืนหรือกำหนดประเภทของรูปแบบเรขาคณิตพรีเซ็ต. หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**ส่งคืน:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ส่งคืนหรือกำหนดประเภทของรูปแบบเรขาคณิตพรีเซ็ต. หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

ส่งคืนคอลเลกชันของค่าการปรับรูปทรง. อ่านอย่างเดียว [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**ส่งคืน:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

สร้างและส่งคืนอาเรย์ขององค์ประกอบของรูปทรง.

**ส่งคืน:**  
com.aspose.slides.IShapeElement[] - อาเรย์ของ [ShapeElement](../../com.aspose.slides/shapeelement)
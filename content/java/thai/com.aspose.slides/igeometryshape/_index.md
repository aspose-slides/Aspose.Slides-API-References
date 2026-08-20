---
title: IGeometryShape
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด
type: docs
url: /th/com.aspose.slides/igeometryshape/
---
**อินเทอร์เฟซที่ทำทั้งหมด:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

แทนคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจกต์ [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | อัปเดตเรขาคณิตของรูปทรงจากอาร์เรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [getShapeStyle()](#getShapeStyle--) | ส่งคืนอ็อบเจกต์สไตล์ของรูปทรง |
| [getShapeType()](#getShapeType--) | ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต |
| [setShapeType(int value)](#setShapeType-int-) | ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต |
| [getAdjustments()](#getAdjustments--) | ส่งคืนคอลเลกชันของค่าการปรับของรูปทรง |
| [createShapeElements()](#createShapeElements--) | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปทรง |

### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต พิกัดจะสัมพันธ์กับมุมบนซ้ายของรูปทรง

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


**คืนค่า:**
com.aspose.slides.IGeometryPath[] - อาร์เรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath)

### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจกต์ [IGeometryPath](../../com.aspose.slides/igeometrypath) พิกัดต้องสัมพันธ์กับมุมบนซ้ายของรูปทรง เปลี่ยนประเภทของรูปทรง (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

อัปเดตเรขาคณิตของรูปทรงจากอาร์เรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath) พิกัดต้องสัมพันธ์กับมุมบนซ้ายของรูปทรง เปลี่ยนประเภทของรูปทรง (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | อาร์เรย์ของเส้นทางเรขาคณิตย์ |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

ส่งคืนอ็อบเจกต์สไตล์ของรูปทรง อ่านอย่างเดียว [IShapeStyle](../../com.aspose.slides/ishapestyle).

**คืนค่า:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)

### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต หมายเหตุ: เมื่อค่าเปลี่ยนแปลง ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**คืนค่า:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต หมายเหตุ: เมื่อค่าเปลี่ยนแปลง ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

ส่งคืนคอลเลกชันของค่าการปรับของรูปทรง อ่านอย่างเดียว [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**คืนค่า:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปทรง.

**คืนค่า:**
com.aspose.slides.IShapeElement[] - อาร์เรย์ของ [IShapeElement](../../com.aspose.slides/ishapeelement)
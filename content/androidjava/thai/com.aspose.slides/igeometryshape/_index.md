---
title: IGeometryShape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงถึงคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
type: docs
url: /th/com.aspose.slides/igeometryshape/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

แสดงถึงคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | อัปเดตเรขาคณิตของ shape จากอ็อบเจ็กต์ [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | อัปเดตเรขาคณิตของ shape จากอาเรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath) |
| [getShapeStyle()](#getShapeStyle--) | ส่งคืนออบเจ็กต์สไตล์ของ shape |
| [getShapeType()](#getShapeType--) | ส่งคืนหรือกำหนดค่าชนิดพรีเซ็ตของเรขาคณิต |
| [setShapeType(int value)](#setShapeType-int-) | ส่งคืนหรือกำหนดค่าชนิดพรีเซ็ตของเรขาคณิต |
| [getAdjustments()](#getAdjustments--) | ส่งคืนชุดของค่าการปรับของ shape |
| [createShapeElements()](#createShapeElements--) | สร้างและส่งคืนอาเรย์ขององค์ประกอบของ shape |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```


ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต พิกัดเป็นค่าที่สัมพันธ์กับมุมซ้ายบนของ shape.

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
public abstract void setGeometryPath(IGeometryPath geometryPath)
```


อัปเดตเรขาคณิตของ shape จากอ็อบเจ็กต์ [IGeometryPath](../../com.aspose.slides/igeometrypath) พิกัดจะต้องสัมพันธ์กับมุมซ้ายบนของ shape การเปลี่ยนประเภทของ shape (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


อัปเดตเรขาคณิตของ shape จากอาเรย์ของ [IGeometryPath](../../com.aspose.slides/igeometrypath) พิกัดจะต้องสัมพันธ์กับมุมซ้ายบนของ shape การเปลี่ยนประเภทของ shape (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) เป็น [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
public abstract IShapeStyle getShapeStyle()
```


ส่งคืนออบเจ็กต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../../com.aspose.slides/ishapestyle).

**ส่งคืน:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```


ส่งคืนหรือกำหนดค่าชนิดพรีเซ็ตของเรขาคณิต หมายเหตุ: เมื่อค่าเปลี่ยนแปลง ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่ามาตรฐานของมัน อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**ส่งคืน:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```


ส่งคืนหรือกำหนดค่าชนิดพรีเซ็ตของเรขาคณิต หมายเหตุ: เมื่อค่าเปลี่ยนแปลง ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่ามาตรฐานของมัน อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```


ส่งคืนชุดของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**ส่งคืน:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```


สร้างและส่งคืนอาเรย์ขององค์ประกอบของ shape.

**ส่งคืน:**
com.aspose.slides.IShapeElement[] - อาเรย์ของ [IShapeElement](../../com.aspose.slides/ishapeelement)
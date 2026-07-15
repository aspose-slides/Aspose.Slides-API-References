---
title: GeometryShape
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện cho lớp cha của tất cả các hình dạng hình học.
type: docs
url: /vi/com.aspose.slides/geometryshape/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Đại diện cho lớp cha của tất cả các hình dạng hình học.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Trả về bản sao của đường dẫn của hình dạng hình học. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Cập nhật hình học của hình dạng từ đối tượng [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Cập nhật hình học của hình dạng từ mảng [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Trả về đối tượng style của hình dạng. |
| [getShapeType()](#getShapeType--) | Trả về hoặc đặt loại preset hình học. |
| [setShapeType(int value)](#setShapeType-int-) | Trả về hoặc đặt loại preset hình học. |
| [getAdjustments()](#getAdjustments--) | Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng. |
| [createShapeElements()](#createShapeElements--) | Tạo và trả về mảng các phần tử của hình dạng. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Trả về bản sao của đường dẫn của hình dạng hình học. Các tọa độ tương đối so với góc trái trên của hình dạng.

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


**Trả về:**
com.aspose.slides.IGeometryPath[] - Mảng của [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Cập nhật hình học của hình dạng từ đối tượng [IGeometryPath](../../com.aspose.slides/igeometrypath). Các tọa độ phải tương đối so với góc trái trên của hình dạng. Thay đổi loại của hình dạng (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) thành [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Đường dẫn hình học |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Cập nhật hình học của hình dạng từ mảng [IGeometryPath](../../com.aspose.slides/igeometrypath). Các tọa độ phải tương đối so với góc trái trên của hình dạng. Thay đổi loại của hình dạng (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) thành [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Mảng các đường dẫn hình học |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Trả về đối tượng style của hình dạng. Chỉ đọc [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Trả về:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Trả về hoặc đặt loại preset hình học. Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về mặc định. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Trả về:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Trả về hoặc đặt loại preset hình học. Lưu ý: khi thay đổi giá trị, tất cả các giá trị điều chỉnh sẽ được đặt lại về mặc định. Đọc/ghi [ShapeType](../../com.aspose.slides/shapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Trả về một bộ sưu tập các giá trị điều chỉnh của hình dạng. Chỉ đọc [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Trả về:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Tạo và trả về mảng các phần tử của hình dạng.

**Trả về:**
com.aspose.slides.IShapeElement[] - Mảng của [ShapeElement](../../com.aspose.slides/shapeelement)
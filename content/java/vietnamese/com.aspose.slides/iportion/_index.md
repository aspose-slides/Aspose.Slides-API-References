---
title: IPortion
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một phần văn bản bên trong một đoạn văn bản.
type: docs
url: /vi/com.aspose.slides/iportion/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Biểu diễn một phần văn bản bên trong một đoạn văn bản.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Trả về đối tượng định dạng chứa các thuộc tính định dạng được đặt một cách rõ ràng của phần văn bản mà không áp dụng kế thừa. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần của một phần. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần của một phần. |
| [getField()](#getField--) | Trả về một trường của phần này. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Chuyển đổi phần này thành trường được cập nhật tự động. |
| [addField(String internalString)](#addField-java.lang.String-) | Chuyển đổi phần này thành trường được cập nhật tự động. |
| [removeField()](#removeField--) | Chuyển đổi phần trường này thành phần đơn giản. |
| [getRect()](#getRect--) | Lấy tọa độ của hình chữ nhật bao quanh phần. |
| [getCoordinates()](#getCoordinates--) | Lấy tọa độ của điểm bắt đầu phần. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Trả về đối tượng định dạng chứa các thuộc tính định dạng được đặt một cách rõ ràng của phần văn bản mà không áp dụng kế thừa. Chỉ đọc [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Đối tượng định dạng chỉ chứa các tham số định dạng được định nghĩa cho phần hiện tại, dữ liệu kế thừa không được áp dụng.

Để lấy các giá trị thực tế bao gồm các giá trị kế thừa, hãy sử dụng phương thức [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Lấy hoặc đặt văn bản thuần của một phần. Đọc/ghi String.

Giá trị: Văn bản.

**Trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Lấy hoặc đặt văn bản thuần của một phần. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Trả về một trường của phần này. Chỉ đọc [IField](../../com.aspose.slides/ifield).

**Trả về:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Chuyển đổi phần này thành trường được cập nhật tự động.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Kiểu của trường [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Chuyển đổi phần này thành trường được cập nhật tự động.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| internalString | java.lang.String | Tên nội bộ của FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Chuyển đổi phần trường này thành phần đơn giản.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Lấy tọa độ của hình chữ nhật bao quanh phần. Hình chữ nhật bao gồm tất cả các dòng văn bản trong phần, bao gồm cả các dòng trống.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
java.awt.geom.Rectangle2D.Float - Hình chữ nhật bao quanh phần java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Lấy tọa độ của điểm bắt đầu phần. Tọa độ X của điểm đại diện cho phần bắt đầu từ ký tự đầu tiên bao gồm phần bên trái. Tọa độ Y bao gồm phần trên.

**Trả về:**
java.awt.geom.Point2D.Float - Tọa độ của điểm bắt đầu phần java.awt.geom.Point2D.Float
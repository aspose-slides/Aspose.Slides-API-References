---
title: Portion
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn một phần văn bản trong một đoạn văn bản.
type: docs
url: /vi/com.aspose.slides/portion/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Biểu diễn một phần văn bản trong một đoạn văn bản.
## Hàm tạo

| Constructor | Description |
| --- | --- |
| [Portion()](#Portion--) | Khởi tạo một thể hiện mới của lớp Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Khởi tạo một thể hiện mới của lớp Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Khởi tạo một thể hiện mới của lớp Portion. |
## Phương thức

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Trả về đối tượng định dạng chứa các thuộc tính định dạng được đặt rõ ràng của phần văn bản mà không áp dụng kế thừa. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần của một phần. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần của một phần. |
| [getField()](#getField--) | Trả về một trường của phần này. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Chuyển đổi phần này thành trường được cập nhật tự động. |
| [addField(String internalString)](#addField-java.lang.String-) | Chuyển đổi phần này thành trường được cập nhật tự động. |
| [removeField()](#removeField--) | Chuyển đổi phần trường này thành phần đơn giản. |
| [getRect()](#getRect--) | Lấy tọa độ của hình chữ nhật bao quanh phần. |
| [getCoordinates()](#getCoordinates--) | Lấy tọa độ của đầu phần. |
| [getSlide()](#getSlide--) | Trả về slide cha của văn bản. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của văn bản. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Khởi tạo một thể hiện mới của lớp Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Khởi tạo một thể hiện mới của lớp Portion.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Khởi tạo một thể hiện mới của lớp Portion.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Trả về đối tượng định dạng chứa các thuộc tính định dạng được đặt rõ ràng của phần văn bản mà không áp dụng kế thừa. Chỉ đọc [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Đối tượng định dạng chứa các tham số định dạng được định nghĩa chỉ cho phần hiện tại, dữ liệu kế thừa không được áp dụng.

Để lấy các giá trị thực tế bao gồm các giá trị kế thừa, sử dụng phương thức [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Lấy hoặc đặt văn bản thuần của một phần. Đọc/ghi String.

Giá trị: Văn bản.

**Trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lấy hoặc đặt văn bản thuần của một phần. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Trả về một trường của phần này. Chỉ đọc [IField](../../com.aspose.slides/ifield).

**Trả về:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Chuyển đổi phần này thành trường được cập nhật tự động.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Chuyển đổi phần này thành trường được cập nhật tự động.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| internalString | java.lang.String | Tên nội bộ của FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Chuyển đổi phần trường này thành phần đơn giản.

### getRect() {#getRect--}
```
public final RectF getRect()
```

Lấy tọa độ của hình chữ nhật bao quanh phần. Hình chữ nhật bao gồm tất cả các dòng văn bản trong phần, kể cả các dòng trống.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Lấy tọa độ của đầu phần. Tọa độ X của điểm đại diện cho bắt đầu phần từ ký tự đầu tiên bao gồm phần bên trái. Tọa độ Y bao gồm phần trên.

**Trả về:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của văn bản. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của văn bản. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
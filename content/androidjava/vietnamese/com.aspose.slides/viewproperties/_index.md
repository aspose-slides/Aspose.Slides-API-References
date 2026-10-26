---
title: ViewProperties
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Thuộc tính xem toàn bộ bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/viewproperties/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Thuộc tính xem toàn bộ bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLastView()](#getLastView--) | Chỉ ra chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. |
| [setLastView(int value)](#setLastView-int-) | Chỉ ra chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. |
| [getShowComments()](#getShowComments--) | Chỉ ra liệu bình luận slide có nên được hiển thị hay không. |
| [setShowComments(byte value)](#setShowComments-byte-) | Chỉ ra liệu bình luận slide có nên được hiển thị hay không. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Đại diện cho các thuộc tính xem bình thường. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Chỉ ra các thuộc tính xem chung liên quan đến chế độ xem slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Chỉ ra các thuộc tính xem chung liên quan đến chế độ xem ghi chú. |
| [getGridSpacing()](#getGridSpacing--) | Trả về hoặc đặt khoảng cách lưới nên được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Trả về hoặc đặt khoảng cách lưới nên được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Chỉ ra chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Trả về:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Chỉ ra chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Chỉ ra liệu bình luận slide có nên được hiển thị hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Chỉ ra liệu bình luận slide có nên được hiển thị hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Đại diện cho các thuộc tính xem bình thường. Chế độ xem bình thường bao gồm ba vùng nội dung: slide, một vùng nội dung phụ và một vùng nội dung phía dưới. Chỉ-đọc [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Trả về:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Chỉ ra các thuộc tính xem chung liên quan đến chế độ xem slide. Chỉ-đọc [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Trả về:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Chỉ ra các thuộc tính xem chung liên quan đến chế độ xem ghi chú. Chỉ-đọc [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Trả về:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Trả về hoặc đặt khoảng cách lưới nên được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. Đọc/ghi float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Giá trị khoảng cách lưới phải là một số dương. Dải giá trị điển hình là từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Trả về:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Trả về hoặc đặt khoảng cách lưới nên được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. Đọc/ghi float.

--------------------

> ```
> Mã mẫu sau đây cho thấy cách thay đổi khoảng cách lưới trong một bản trình chiếu PowerPoint.
>  
  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Giá trị khoảng cách lưới phải là một số dương. Dải giá trị điển hình là từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ-đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
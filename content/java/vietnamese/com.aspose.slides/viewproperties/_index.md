---
title: ViewProperties
second_title: Tham chiếu API Aspose.Slides cho Java
description: Thuộc tính chế độ xem toàn bộ bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/viewproperties/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Thuộc tính chế độ xem toàn bộ bản trình chiếu.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getLastView()](#getLastView--) | Chỉ định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. |
| [setLastView(int value)](#setLastView-int-) | Chỉ định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. |
| [getShowComments()](#getShowComments--) | Chỉ định liệu bình luận slide có nên được hiển thị hay không. |
| [setShowComments(byte value)](#setShowComments-byte-) | Chỉ định liệu bình luận slide có nên được hiển thị hay không. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Biểu diễn các thuộc tính chế độ xem bình thường. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Chỉ định các thuộc tính chế độ xem chung liên quan đến chế độ xem slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Chỉ định các thuộc tính chế độ xem chung liên quan đến chế độ xem ghi chú. |
| [getGridSpacing()](#getGridSpacing--) | Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

Chỉ định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Trả về:**
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Chỉ định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Chỉ định liệu bình luận slide có nên được hiển thị hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Chỉ định liệu bình luận slide có nên được hiển thị hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Biểu diễn các thuộc tính chế độ xem bình thường. Chế độ xem bình thường bao gồm ba vùng nội dung: slide, một vùng nội dung phụ, và một vùng nội dung phía dưới. Đọc-chỉ [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Trả về:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Chỉ định các thuộc tính chế độ xem chung liên quan đến chế độ xem slide. Đọc-chỉ [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Trả về:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Chỉ định các thuộc tính chế độ xem chung liên quan đến chế độ xem ghi chú. Đọc-chỉ [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Trả về:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. Đọc/ghi float.

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

Giá trị khoảng cách lưới phải là số dương. Phạm vi giá trị thường là từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Trả về:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu bản trình chiếu, tính bằng điểm. Đọc/ghi float.

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

Giá trị khoảng cách lưới phải là số dương. Phạm vi giá trị thường là từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Đọc-chỉ IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
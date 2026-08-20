---
title: IViewProperties
second_title: Tham chiếu API Aspose.Slides cho Java
description: Thuộc tính chế độ xem toàn bộ bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Thuộc tính chế độ xem toàn bộ bản trình chiếu.
## Các phương thức

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Xác định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. |
| [setLastView(int value)](#setLastView-int-) | Xác định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. |
| [getShowComments()](#getShowComments--) | Xác định liệu các bình luận của slide có được hiển thị hay không. |
| [setShowComments(byte value)](#setShowComments-byte-) | Xác định liệu các bình luận của slide có được hiển thị hay không. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Xác định các thuộc tính chế độ xem chung liên quan đến chế độ xem slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Xác định các thuộc tính chế độ xem chung liên quan đến chế độ xem ghi chú. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Đại diện cho các thuộc tính chế độ xem bình thường. |
| [getGridSpacing()](#getGridSpacing--) | Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới cơ bản của tài liệu bản trình chiếu, tính bằng điểm. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới cơ bản của tài liệu bản trình chiếu, tính bằng điểm. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Xác định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Returns:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Xác định chế độ xem đã được sử dụng khi tài liệu bản trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Xác định liệu các bình luận của slide có được hiển thị hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Xác định liệu các bình luận của slide có được hiển thị hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Xác định các thuộc tính chế độ xem chung liên quan đến chế độ xem slide. Chỉ đọc [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Xác định các thuộc tính chế độ xem chung liên quan đến chế độ xem ghi chú. Chỉ đọc [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Đại diện cho các thuộc tính chế độ xem bình thường. Chế độ xem bình thường bao gồm ba vùng nội dung: slide, một vùng nội dung bên cạnh và một vùng nội dung phía dưới. Chỉ đọc [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returns:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới cơ bản của tài liệu bản trình chiếu, tính bằng điểm. Đọc/ghi float.

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

Giá trị khoảng cách lưới phải là một số dương. Khoảng giá trị điển hình từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Returns:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới cơ bản của tài liệu bản trình chiếu, tính bằng điểm. Đọc/ghi float.

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

Giá trị khoảng cách lưới phải là một số dương. Khoảng giá trị điển hình từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
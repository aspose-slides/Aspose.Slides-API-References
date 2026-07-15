---
title: IViewProperties
second_title: Aspose.Slides cho Android via Java API Reference
description: Thuộc tính hiển thị trên toàn bộ bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Thuộc tính hiển thị trên toàn bộ bài thuyết trình.
## Phương thức

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Xác định chế độ xem đã được sử dụng khi tài liệu trình chiếu được lưu lần cuối. |
| [setLastView(int value)](#setLastView-int-) | Xác định chế độ xem đã được sử dụng khi tài liệu trình chiếu được lưu lần cuối. |
| [getShowComments()](#getShowComments--) | Xác định có nên hiển thị bình luận slide hay không. |
| [setShowComments(byte value)](#setShowComments-byte-) | Xác định có nên hiển thị bình luận slide hay không. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Xác định các thuộc tính hiển thị chung liên quan đến chế độ xem slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Xác định các thuộc tính hiển thị chung liên quan đến chế độ xem ghi chú. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Biểu diễn các thuộc tính hiển thị bình thường. |
| [getGridSpacing()](#getGridSpacing--) | Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu trình chiếu, tính bằng điểm. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu trình chiếu, tính bằng điểm. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Xác định chế độ xem đã được sử dụng khi tài liệu trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Trả về:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Xác định chế độ xem đã được sử dụng khi tài liệu trình chiếu được lưu lần cuối. Đọc/ghi [ViewType](../../com.aspose.slides/viewtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Xác định có nên hiển thị bình luận slide hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Xác định có nên hiển thị bình luận slide hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Xác định các thuộc tính hiển thị chung liên quan đến chế độ xem slide. Chỉ đọc [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Trả về:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Xác định các thuộc tính hiển thị chung liên quan đến chế độ xem ghi chú. Chỉ đọc [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Trả về:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Biểu diễn các thuộc tính hiển thị bình thường. Khi hiển thị bình thường bao gồm ba vùng nội dung: slide, một vùng nội dung bên và một vùng nội dung dưới. Chỉ đọc [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Trả về:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu trình chiếu, tính bằng điểm. Đọc/ghi float.

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

Giá trị khoảng cách lưới phải là số dương. Dải giá trị điển hình là từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Trả về:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Trả về hoặc đặt khoảng cách lưới sẽ được sử dụng cho lưới nền của tài liệu trình chiếu, tính bằng điểm. Đọc/ghi float.

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

Giá trị khoảng cách lưới phải là số dương. Dải giá trị điển hình là từ 1 mm (2.8349607 điểm) đến 2 inch (144 điểm).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
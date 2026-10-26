---
title: NormalViewProperties
second_title: Tham chiếu API Java Aspose.Slides cho Android
description: Đại diện cho các thuộc tính của chế độ xem bình thường.
type: docs
url: /vi/com.aspose.slides/normalviewproperties/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các giao diện được triển khai:**  
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)  
```
public class NormalViewProperties implements INormalViewProperties
```

Đại diện cho các thuộc tính của chế độ xem bình thường. Chế độ xem bình thường bao gồm ba vùng nội dung: slide, một vùng nội dung bên, và một vùng nội dung phía dưới.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Khởi tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Method | Mô tả |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Xác định xem ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Xác định xem ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Xác định xem bộ chia dọc có nên bật tới trạng thái thu gọn khi vùng bên đủ nhỏ hay không. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Xác định xem bộ chia dọc có nên bật tới trạng thái thu gọn khi vùng bên đủ nhỏ hay không. |
| [getVerticalBarState()](#getVerticalBarState--) | Xác định trạng thái hiển thị của thanh bộ chia dọc. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Xác định trạng thái hiển thị của thanh bộ chia dọc. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Xác định trạng thái hiển thị của thanh bộ chia ngang. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Xác định trạng thái hiển thị của thanh bộ chia ngang. |
| [getPreferSingleView()](#getPreferSingleView--) | Xác định xem người dùng có muốn xem một vùng nội dung đơn toàn màn hình thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Xác định xem người dùng có muốn xem một vùng nội dung đơn toàn màn hình thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. |
| [getRestoredLeft()](#getRestoredLeft--) | Phần tử này xác định kích thước của vùng nội dung bên trong chế độ xem bình thường, khi vùng này có kích thước khôi phục biến đổi (không thu gọn và không phóng to). |
| [getRestoredTop()](#getRestoredTop--) | Phần tử này xác định kích thước của vùng slide trên trong chế độ xem bình thường, khi vùng này có kích thước khôi phục biến đổi (không thu gọn và không phóng to). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Xác định xem ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. Đọc/ghi boolean.

**Trả về:**  
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Xác định xem ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Xác định xem bộ chia dọc có nên bật tới trạng thái thu gọn khi vùng bên đủ nhỏ hay không. Đọc/ghi boolean.

**Trả về:**  
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Xác định xem bộ chia dọc có nên bật tới trạng thái thu gọn khi vùng bên đủ nhỏ hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Xác định trạng thái hiển thị của thanh bộ chia dọc. Thanh bộ chia dọc tách slide ra khỏi vùng nội dung bên.

**Trả về:**  
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Xác định trạng thái hiển thị của thanh bộ chia dọc. Thanh bộ chia dọc tách slide ra khỏi vùng nội dung bên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Xác định trạng thái hiển thị của thanh bộ chia ngang. Thanh bộ chia ngang tách slide ra khỏi vùng nội dung phía dưới slide.

**Trả về:**  
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Xác định trạng thái hiển thị của thanh bộ chia ngang. Thanh bộ chia ngang tách slide ra khỏi vùng nội dung phía dưới slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Xác định xem người dùng có muốn xem một vùng nội dung đơn toàn màn hình thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. Nếu bật, ứng dụng có thể chọn hiển thị một trong các vùng nội dung trên toàn cửa sổ. Đọc/ghi boolean.

**Trả về:**  
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Xác định xem người dùng có muốn xem một vùng nội dung đơn toàn màn hình thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. Nếu bật, ứng dụng có thể chọn hiển thị một trong các vùng nội dung trên toàn cửa sổ. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Phần tử này xác định kích thước của vùng nội dung bên trong chế độ xem bình thường, khi vùng này có kích thước khôi phục biến đổi (không thu gọn và không phóng to). Chỉ đọc [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Trả về:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Phần tử này xác định kích thước của vùng slide trên trong chế độ xem bình thường, khi vùng này có kích thước khôi phục biến đổi (không thu gọn và không phóng to). Chỉ đọc [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Trả về:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
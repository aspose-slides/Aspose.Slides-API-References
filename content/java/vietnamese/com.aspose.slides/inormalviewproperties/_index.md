---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho các thuộc tính chế độ xem bình thường.
type: docs
url: /vi/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Biểu diễn các thuộc tính chế độ xem bình thường. Chế độ xem bình thường gồm ba vùng nội dung: bản slide, một vùng nội dung bên và một vùng nội dung phía dưới.
## Phương thức

| Method | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) |  |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) |  |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) |  |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) |  |
| [getVerticalBarState()](#getVerticalBarState--) |  |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) |  |
| [getHorizontalBarState()](#getHorizontalBarState--) |  |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) |  |
| [getPreferSingleView()](#getPreferSingleView--) |  |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) |  |
| [getRestoredLeft()](#getRestoredLeft--) |  |
| [getRestoredTop()](#getRestoredTop--) |  |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Xác định liệu ứng dụng có hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Xác định liệu ứng dụng có hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Xác định liệu thanh chia dọc có tự động thu gọn khi vùng bên đủ nhỏ hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Xác định liệu thanh chia dọc có tự động thu gọn khi vùng bên đủ nhỏ hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Xác định trạng thái mà thanh chia dọc sẽ được hiển thị. Thanh chia dọc tách slide khỏi vùng nội dung bên.

**Trả về:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Xác định trạng thái mà thanh chia dọc sẽ được hiển thị. Thanh chia dọc tách slide khỏi vùng nội dung bên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Xác định trạng thái mà thanh chia ngang sẽ được hiển thị. Thanh chia ngang tách slide khỏi vùng nội dung phía dưới slide.

**Trả về:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Xác định trạng thái mà thanh chia ngang sẽ được hiển thị. Thanh chia ngang tách slide khỏi vùng nội dung phía dưới slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Xác định liệu người dùng muốn xem một vùng nội dung duy nhất toàn màn hình thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. Nếu bật, ứng dụng có thể chọn hiển thị một trong các vùng nội dung trên toàn cửa sổ. Đọc/ghi boolean.

**Trả về:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Xác định liệu người dùng muốn xem một vùng nội dung duy nhất toàn màn hình thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. Nếu bật, ứng dụng có thể chọn hiển thị một trong các vùng nội dung trên toàn cửa sổ. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Phần tử này xác định kích thước của vùng nội dung bên trong chế độ xem bình thường, khi vùng này có kích thước khôi phục biến đổi (không thu nhỏ cũng không phóng to). Chỉ đọc [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Trả về:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Phần tử này xác định kích thước của vùng slide trên cùng của chế độ xem bình thường, khi vùng này có kích thước khôi phục biến đổi (không thu nhỏ cũng không phóng to). Chỉ đọc [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Trả về:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
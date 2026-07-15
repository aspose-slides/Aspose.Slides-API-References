---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho các thuộc tính của chế độ xem bình thường.
type: docs
url: /vi/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Đại diện cho các thuộc tính của chế độ xem bình thường. Chế độ xem bình thường bao gồm ba vùng nội dung: bản trình chiếu, một vùng nội dung bên và một vùng nội dung dưới.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Cho biết ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Cho biết ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Cho biết thanh chia dọc có nên chốt vào trạng thái thu nhỏ khi vùng bên đủ nhỏ hay không. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Cho biết thanh chia dọc có nên chốt vào trạng thái thu nhỏ khi vùng bên đủ nhỏ hay không. |
| [getVerticalBarState()](#getVerticalBarState--) | Xác định trạng thái mà thanh chia dọc sẽ được hiển thị. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Xác định trạng thái mà thanh chia dọc sẽ được hiển thị. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Xác định trạng thái mà thanh chia ngang sẽ được hiển thị. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Xác định trạng thái mà thanh chia ngang sẽ được hiển thị. |
| [getPreferSingleView()](#getPreferSingleView--) | Cho biết người dùng muốn xem một vùng nội dung đơn toàn cửa sổ thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Cho biết người dùng muốn xem một vùng nội dung đơn toàn cửa sổ thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. |
| [getRestoredLeft()](#getRestoredLeft--) | Phần tử này chỉ định kích thước của vùng nội dung bên của chế độ xem bình thường, khi vùng này có kích thước phục hồi thay đổi (không thu nhỏ cũng không phóng to). |
| [getRestoredTop()](#getRestoredTop--) | Phần tử này chỉ định kích thước của vùng bản trình chiếu phía trên của chế độ xem bình thường, khi vùng này có kích thước phục hồi thay đổi (không thu nhỏ cũng không phóng to). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Cho biết ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Cho biết ứng dụng có nên hiển thị biểu tượng khi hiển thị nội dung đề cương trong bất kỳ vùng nội dung nào của chế độ xem bình thường hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Cho biết thanh chia dọc có nên chốt vào trạng thái thu nhỏ khi vùng bên đủ nhỏ hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Cho biết thanh chia dọc có nên chốt vào trạng thái thu nhỏ khi vùng bên đủ nhỏ hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Xác định trạng thái mà thanh chia dọc sẽ được hiển thị. Thanh chia dọc tách bản trình chiếu khỏi vùng nội dung bên.

**Trả về:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Xác định trạng thái mà thanh chia dọc sẽ được hiển thị. Thanh chia dọc tách bản trình chiếu khỏi vùng nội dung bên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Xác định trạng thái mà thanh chia ngang sẽ được hiển thị. Thanh chia ngang tách bản trình chiếu khỏi vùng nội dung phía dưới bản trình chiếu.

**Trả về:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Xác định trạng thái mà thanh chia ngang sẽ được hiển thị. Thanh chia ngang tách bản trình chiếu khỏi vùng nội dung phía dưới bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Cho biết người dùng muốn xem một vùng nội dung đơn toàn cửa sổ thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. Nếu bật, ứng dụng có thể chọn hiển thị một trong các vùng nội dung trên toàn cửa sổ. Đọc/ghi boolean.

**Trả về:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Cho biết người dùng muốn xem một vùng nội dung đơn toàn cửa sổ thay vì chế độ xem bình thường tiêu chuẩn với ba vùng nội dung hay không. Nếu bật, ứng dụng có thể chọn hiển thị một trong các vùng nội dung trên toàn cửa sổ. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Phần tử này chỉ định kích thước của vùng nội dung bên của chế độ xem bình thường, khi vùng này có kích thước phục hồi thay đổi (không thu nhỏ cũng không phóng to). Chỉ đọc [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Trả về:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Phần tử này chỉ định kích thước của vùng bản trình chiếu phía trên của chế độ xem bình thường, khi vùng này có kích thước phục hồi thay đổi (không thu nhỏ cũng không phóng to). Chỉ đọc [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Trả về:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
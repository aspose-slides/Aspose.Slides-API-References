---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Xác định kích thước của vùng slide (độ rộng khi là con của restoredTop, độ cao khi là con của restoredLeft) của chế độ xem bình thường, khi vùng này có kích thước restored biến đổi (không bị thu nhỏ hay phóng to).
type: docs
url: /vi/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

Xác định kích thước của vùng slide ((độ rộng khi là con của restoredTop, độ cao khi là con của restoredLeft) của chế độ xem bình thường, khi vùng này có kích thước restored biến đổi (không bị thu nhỏ hay phóng to)).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | Xác định kích thước của vùng slide (độ rộng khi là con của RestoredTop, độ cao khi là con của RestoredLeft). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | Xác định kích thước của vùng slide (độ rộng khi là con của RestoredTop, độ cao khi là con của RestoredLeft). |
| [getAutoAdjust()](#getAutoAdjust--) | Xác định liệu kích thước của vùng nội dung phụ có nên bù cho kích thước mới khi thay đổi kích thước cửa sổ chứa chế độ xem trong ứng dụng hay không. Đọc/ghi boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | Xác định liệu kích thước của vùng nội dung phụ có nên bù cho kích thước mới khi thay đổi kích thước cửa sổ chứa chế độ xem trong ứng dụng hay không. Đọc/ghi boolean. |
### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

Xác định kích thước của vùng slide (độ rộng khi là con của RestoredTop, độ cao khi là con của RestoredLeft). Đọc/ghi float.

**Trả về:**
float
### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

Xác định kích thước của vùng slide (độ rộng khi là con của RestoredTop, độ cao khi là con của RestoredLeft). Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

Xác định liệu kích thước của vùng nội dung phụ có nên bù cho kích thước mới khi thay đổi kích thước cửa sổ chứa chế độ xem trong ứng dụng hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

Xác định liệu kích thước của vùng nội dung phụ có nên bù cho kích thước mới khi thay đổi kích thước cửa sổ chứa chế độ xem trong ứng dụng hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
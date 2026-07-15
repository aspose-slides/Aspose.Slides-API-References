---
title: IXpsOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng XPS.
type: docs
url: /vi/com.aspose.slides/ixpsoptions/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng XPS.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Đúng để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Đúng để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Đúng để vẽ khung đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Đúng để vẽ khung đen quanh mỗi slide. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


Đúng để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Trả về:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


Đúng để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


Đúng để vẽ khung đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


Đúng để vẽ khung đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
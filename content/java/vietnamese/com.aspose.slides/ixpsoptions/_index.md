---
title: IXpsOptions
second_title: Tham chiếu API Aspose.Slides cho Java
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
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True để vẽ khung màu đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True để vẽ khung màu đen quanh mỗi slide. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/ghi boolean.

--------------------

Mặc định là **true**.

**Trả về:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/ghi boolean.

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

True để vẽ khung màu đen quanh mỗi slide. Đọc/ghi boolean.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True để vẽ khung màu đen quanh mỗi slide. Đọc/ghi boolean.

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

Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là **false**.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
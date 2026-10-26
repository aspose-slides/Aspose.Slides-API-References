---
title: XpsOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng XPS.
type: docs
url: /vi/com.aspose.slides/xpsoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp bản trình chiếu
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Lưu bản trình chiếu thành tài liệu XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp bản trình chiếu
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Khởi tạo lớp TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Lưu MetaFiles dưới dạng PNG
>      options.setSaveMetafilesAsPng(true);
>      // Lưu bản trình chiếu thành tài liệu XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Bộ khởi tạo

| Bộ khởi tạo | Mô tả |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Hàm khởi tạo mặc định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True để chuyển đổi tất cả các metafile được sử dụng trong một bản trình chiếu thành các hình ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True để chuyển đổi tất cả các metafile được sử dụng trong một bản trình chiếu thành các hình ảnh PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True để vẽ khung đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True để vẽ khung đen quanh mỗi slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Hàm khởi tạo mặc định.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


True để chuyển đổi tất cả các metafile được sử dụng trong một bản trình chiếu thành các hình ảnh PNG. Boolean đọc/ghi.

--------------------

Mặc định là **true**.

**Trả về:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


True để chuyển đổi tất cả các metafile được sử dụng trong một bản trình chiếu thành các hình ảnh PNG. Boolean đọc/ghi.

--------------------

Mặc định là **true**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


True để vẽ khung đen quanh mỗi slide. Boolean đọc/ghi.

--------------------

Mặc định là **false**.

**Trả về:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True để vẽ khung đen quanh mỗi slide. Boolean đọc/ghi.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
---
title: XpsOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng XPS.
type: docs
url: /vi/com.aspose.slides/xpsoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Lưu trình chiếu dưới dạng tài liệu XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Tạo một đối tượng lớp TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Lưu MetaFiles dưới dạng PNG
>      options.setSaveMetafilesAsPng(true);
>      // Lưu trình chiếu dưới dạng tài liệu XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Hàm khởi tạo mặc định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Chỉ định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Chỉ định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Đặt true để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành các hình ảnh PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Đặt true để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành các hình ảnh PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Đặt true để vẽ khung đen quanh mỗi slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Đặt true để vẽ khung đen quanh mỗi slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Hàm khởi tạo mặc định.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Chỉ định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Giá trị trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Chỉ định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Đặt true để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành các hình ảnh PNG. boolean đọc/ghi.

--------------------

Mặc định là **true**.

**Giá trị trả về:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Đặt true để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu thành các hình ảnh PNG. boolean đọc/ghi.

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

Đặt true để vẽ khung đen quanh mỗi slide. boolean đọc/ghi.

--------------------

Mặc định là **false**.

**Giá trị trả về:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Đặt true để vẽ khung đen quanh mỗi slide. boolean đọc/ghi.

--------------------

Mặc định là **false**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
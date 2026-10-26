---
title: SlideImageFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định định dạng mà ảnh slide sẽ được lưu cho việc xuất trình chiếu sang HTML.
type: docs
url: /vi/com.aspose.slides/slideimageformat/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Xác định định dạng mà ảnh slide sẽ được lưu cho việc xuất sang HTML.

## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Các slide sẽ được chuyển đổi sang định dạng SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Các slide sẽ được chuyển đổi sang hình ảnh raster. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Các slide sẽ được chuyển đổi sang định dạng SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Tùy chọn cho xuất SVG. |

**Giá trị trả về:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Đối tượng [SlideImageFormat](../../com.aspose.slides/slideimageformat).

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Các slide sẽ được chuyển đổi sang hình ảnh raster.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scale | float | Hệ số cho phép thu phóng hình ảnh đầu ra. |
| imageFormat | int | Định dạng của hình ảnh kết quả (ví dụ: PNG, JPEG). |

**Giá trị trả về:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
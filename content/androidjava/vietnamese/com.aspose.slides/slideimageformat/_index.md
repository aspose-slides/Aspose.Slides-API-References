---
title: SlideImageFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Xác định định dạng mà hình ảnh slide sẽ được lưu khi xuất bản trình chiếu sang HTML.
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

Xác định định dạng mà hình ảnh slide sẽ được lưu khi xuất bản trình chiếu sang HTML.

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slides should converted to a SVG format. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slides should be converted to a raster image. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Các slide nên được chuyển đổi sang định dạng SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Tùy chọn cho việc xuất SVG. |

**Trả về:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Đối tượng [SlideImageFormat](../../com.aspose.slides/slideimageformat).

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Các slide nên được chuyển đổi sang hình ảnh raster.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scale | float | Hệ số mở rộng ảnh đầu ra. |
| imageFormat | int | Định dạng của ảnh kết quả (ví dụ: PNG, JPEG). |

**Trả về:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
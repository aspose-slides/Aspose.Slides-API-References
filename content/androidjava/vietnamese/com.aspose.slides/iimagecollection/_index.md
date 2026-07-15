---
title: IImageCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn tập hợp của PPImage.
type: docs
url: /vi/com.aspose.slides/iimagecollection/
---
**Tất cả các giao diện đã thực thi:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Biểu diễn tập hợp của PPImage.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về ảnh theo chỉ mục của nó. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Thêm một hình ảnh vào bản trình chiếu. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Thêm một hình ảnh vào bản trình chiếu từ luồng. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Tạo và thêm một hình ảnh vào bản trình chiếu từ luồng. |
| [addImage(byte[] buffer)](#addImage-byte---) | Thêm một hình ảnh vào bản trình chiếu từ bộ đệm đã chỉ định. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Thêm một bản sao của hình ảnh từ một bản trình chiếu khác. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Thêm một hình ảnh vào bản trình chiếu từ đối tượng SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Trả về ảnh theo chỉ mục của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Thêm một hình ảnh vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Hình ảnh để thêm.

--------------------

Phương thức này chuyển đổi các tệp metafile WMF/EMF sang ảnh PNG raster trước khi chèn vào bản trình chiếu. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Thêm một hình ảnh vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm hình ảnh từ.

--------------------

Phương thức này có thể thêm các tệp metafile WMF/EMF vào bản trình chiếu mà không chuyển đổi chúng sang ảnh PNG raster. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Tạo và thêm một hình ảnh vào bản trình chiếu từ luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng để thêm tệp hình ảnh từ. |
| loadingStreamBehavior | int | Hành vi sẽ được áp dụng cho luồng. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Thêm một hình ảnh vào bản trình chiếu từ bộ đệm đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| buffer | byte[] | Bộ đệm. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Thêm một bản sao của hình ảnh từ một bản trình chiếu khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh nguồn. |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Thêm một hình ảnh vào bản trình chiếu từ đối tượng SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Đối tượng ảnh SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage) - Đã thêm image.
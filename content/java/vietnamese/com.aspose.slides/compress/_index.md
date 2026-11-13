---
title: Compress
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một nhóm các phương thức nhằm nén .
type: docs
url: /vi/com.aspose.slides/compress/
---
**Kế thừa:**
java.lang.Object
```
public class Compress
```

Đại diện cho một nhóm các phương thức nhằm nén [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [Compress()](#Compress--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Giảm kích thước của một bản trình bày bằng cách áp dụng tất cả các bước nén có sẵn:

 *  Loại bỏ các slide master không sử dụng \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Loại bỏ các slide bố cục không sử dụng \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Giữ lại chỉ các glyph thực tế được sử dụng trong phông chữ nhúng \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Giảm độ phân giải hình ảnh xuống 150 DPI và xóa các khu vực đã cắt của hình ảnh \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide master không sử dụng. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide bố cục không sử dụng. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các ký tự không sử dụng khỏi phông chữ nhúng. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Giảm độ phân giải của hình ảnh trong bản trình bày và xóa các khu vực đã cắt, tương tự như tính năng "Compress Pictures" của PowerPoint được áp dụng cho tất cả hình ảnh. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Giảm kích thước của một bản trình bày bằng cách áp dụng tất cả các bước nén có sẵn:

 *  Loại bỏ các slide master không sử dụng \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Loại bỏ các slide bố cục không sử dụng \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Giữ lại chỉ các glyph thực tế được sử dụng trong phông chữ nhúng \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Giảm độ phân giải hình ảnh xuống 150 DPI và xóa các khu vực đã cắt của hình ảnh \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Bản trình bày cần nén.

--------------------

Để tùy chỉnh quá trình nén, ví dụ để sử dụng độ phân giải hình ảnh khác hoặc bỏ qua một bước, hãy gọi các phương thức đã liệt kê ở trên riêng lẻ thay vì phương thức này. Các khu vực đã cắt của hình ảnh sẽ bị xóa vĩnh viễn và không thể khôi phục trong PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide master không sử dụng.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Đối tượng bản trình bày |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide bố cục không sử dụng.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Đối tượng bản trình bày |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các ký tự không sử dụng khỏi phông chữ nhúng.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Đối tượng bản trình bày |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Giảm độ phân giải của hình ảnh trong bản trình bày và xóa các khu vực đã cắt, tương tự như tính năng "Compress Pictures" của PowerPoint được áp dụng cho tất cả hình ảnh. Hình ảnh trên slide, slide bố cục và slide master đều được xử lý, bao gồm cả hình ảnh bên trong các nhóm hình dạng và các hình ảnh được sử dụng làm nền cho các hình dạng.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày cần xử lý. |
| resolution | int | Độ phân giải mục tiêu so với kích thước mà mỗi hình ảnh được hiển thị. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) để lại hình ảnh không thay đổi.

Hình ảnh đã ở mức độ phân giải mục tiêu hoặc thấp hơn sẽ được giữ nguyên; hình ảnh sẽ không bao giờ được tăng kích thước.

Không được xử lý: nền slide, nền ô bảng, biểu đồ, SmartArt, ảnh GIF (để bảo tồn hoạt ảnh), ảnh SVG và metafile (EMF/WMF).

Các khu vực đã cắt sẽ bị xóa vĩnh viễn và không thể khôi phục trong PowerPoint. |
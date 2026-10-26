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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide chủ không dùng. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide bố cục không dùng. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các ký tự không dùng khỏi phông chữ nhúng. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide chủ không dùng.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Thể hiện của bản trình chiếu |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide bố cục không dùng.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Thể hiện của bản trình chiếu |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các ký tự không dùng khỏi phông chữ nhúng.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Thể hiện của bản trình chiếu |
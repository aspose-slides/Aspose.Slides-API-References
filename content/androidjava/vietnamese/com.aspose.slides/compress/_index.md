---
title: Compress
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
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

| Constructor | Mô tả |
| --- | --- |
| [Compress()](#Compress--) |  |
## Phương thức

| Method | Mô tả |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide chủ không sử dụng. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide bố trí không sử dụng. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các ký tự không sử dụng khỏi các phông chữ nhúng. |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide chủ không sử dụng.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Thực thể trình chiếu |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các slide bố trí không sử dụng.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Thực thể trình chiếu |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

Thực hiện nén [Presentation](../../com.aspose.slides/presentation) bằng cách loại bỏ các ký tự không sử dụng khỏi các phông chữ nhúng.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Thực thể trình chiếu |
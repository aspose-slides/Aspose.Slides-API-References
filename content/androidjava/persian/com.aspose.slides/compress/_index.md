---
title: Compress
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک گروه از متدهایی است که برای فشرده‌سازی هدف دارند.
type: docs
url: /fa/com.aspose.slides/compress/
---
**وراثت:**
java.lang.Object
```
public class Compress
```

نمایانگر یک گروه از متدهایی است که برای فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) هدف دارند.

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
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Compress()](#Compress--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف اسلایدهای اصلی استفاده نشده انجام می‌دهد. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف اسلایدهای چیدمان استفاده نشده انجام می‌دهد. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف کاراکترهای استفاده نشده از قلم‌های جاسازی‌شده انجام می‌دهد. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف اسلایدهای اصلی استفاده نشده انجام می‌دهد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | نمونهٔ ارائه |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف اسلایدهای چیدمان استفاده نشده انجام می‌دهد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | نمونهٔ ارائه |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف کاراکترهای استفاده نشده از قلم‌های جاسازی‌شده انجام می‌دهد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | نمونهٔ ارائه |
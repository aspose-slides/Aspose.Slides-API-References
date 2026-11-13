---
title: Compress
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر گروهی از متدهایی است که برای فشرده‌سازی طراحی شده‌اند.
type: docs
url: /fa/com.aspose.slides/compress/
---
**ارث‌بری:**
java.lang.Object
```
public class Compress
```

نمایانگر گروهی از متدهایی است که برای فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) طراحی شده‌اند.

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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | فشرده‌سازی یک ارائه را با اعمال تمام گام‌های فشرده‌سازی موجود انجام می‌دهد:

 *  \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation) اسلایدهای اصلی استفاده نشده را حذف می‌کند.
 *  \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation) اسلایدهای چیدمان استفاده نشده را حذف می‌کند.
 *  \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation) فقط گلیف‌های واقعاً استفاده شده در فونت‌های جاسازی‌شده را نگه می‌دارد.
 *  \#compressImages(IPresentation,int).compressImages(IPresentation,int) وضوح تصویر را به 150 DPI کاهش می‌دهد و نواحی برش‌خورده تصاویر را حذف می‌کند. |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف اسلایدهای اصلی استفاده نشده انجام می‌دهد. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف اسلایدهای چیدمان استفاده نشده انجام می‌دهد. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف حروف استفاده نشده از فونت‌های جاسازی‌شده انجام می‌دهد. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | وضوح تصاویر در ارائه را کاهش می‌دهد و نواحی برش‌خورده آن‌ها را حذف می‌کند، مشابه «Compress Pictures» در PowerPoint که برای تمام تصاویر اعمال می‌شود. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


فشرده‌سازی یک ارائه را با اعمال تمام گام‌های فشرده‌سازی موجود انجام می‌دهد:

 *  \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation) اسلایدهای اصلی استفاده نشده را حذف می‌کند.
 *  \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation) اسلایدهای چیدمان استفاده نشده را حذف می‌کند.
 *  \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation) فقط گلیف‌های واقعاً استفاده شده در فونت‌های جاسازی‌شده را نگه می‌دارد.
 *  \#compressImages(IPresentation,int).compressImages(IPresentation,int) وضوح تصویر را به 150 DPI کاهش می‌دهد و نواحی برش‌خورده تصاویر را حذف می‌کند.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ای که باید فشرده شود. |

--------------------

برای سفارشی‌سازی فشرده‌سازی، به‌عنوان مثال برای استفاده از وضوح تصویر متفاوت یا برای صرف‌نظر کردن از یک گام، به‌جای این متد، متدهای فهرست‌شده در بالا را به‌صورت جداگانه فراخوانی کنید. نواحی برش‌خورده تصاویر به‌صورت دائم حذف می‌شوند و در PowerPoint قابل بازیابی نیستند. |

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
| pres | [Presentation](../../com.aspose.slides/presentation) | نمونه ارائه |

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
| pres | [Presentation](../../com.aspose.slides/presentation) | نمونه ارائه |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

فشرده‌سازی [Presentation](../../com.aspose.slides/presentation) را با حذف حروف استفاده نشده از فونت‌های جاسازی‌شده انجام می‌دهد.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | نمونه ارائه |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

وضوح تصاویر در ارائه را کاهش می‌دهد و نواحی برش‌خورده آن‌ها را حذف می‌کند، مشابه «Compress Pictures» در PowerPoint که برای تمام تصاویر اعمال می‌شود. تصاویر در اسلایدها، اسلایدهای چیدمان و اسلایدهای اصلی پردازش می‌شوند، از جمله تصاویر داخل اشکال گروهی و پرشدن تصویری اشکال.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که باید پردازش شود. |
| resolution | int | وضوح هدف نسبت به اندازه‌ای که هر تصویر در آن نمایش داده می‌شود. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) تصاویر را بدون تغییر می‌گذارد.

تصاویر که از قبل دارای وضوح هدف یا کمتر هستند بدون تغییر می‌مانند؛ تصاویر هرگز بزرگ‌نمایی نمی‌شوند.

پردازش نمی‌شوند: پس‌زمینه‌های اسلاید، پرشدن سلول‌های جدول، نمودارها، SmartArt، تصاویر GIF (برای حفظ انیمیشن)، تصاویر SVG و متافایل (EMF/WMF).

نواحی برش‌خورده به‌صورت دائم حذف می‌شوند و در PowerPoint قابل بازیابی نیستند. |
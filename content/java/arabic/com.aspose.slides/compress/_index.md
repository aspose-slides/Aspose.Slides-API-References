---
title: Compress
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من الأساليب المصممة لضغط .
type: docs
url: /ar/com.aspose.slides/compress/
---
**الوراثة:**  
java.lang.Object  
```
public class Compress
```

يمثل مجموعة من الأساليب المصممة لضغط [Presentation](../../com.aspose.slides/presentation).

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
## المنشآت

| المنشئ | الوصف |
| --- | --- |
| [Compress()](#Compress--) |  |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | يقلل حجم عرض تقديمي عن طريق تطبيق جميع خطوات الضغط المتاحة:

 *  يزيل الشرائح الأساسية غير المستخدمة \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  يزيل شرائح التخطيط غير المستخدمة \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  يحتفظ فقط بالرموز المستخدمة فعليًا في الخطوط المدمجة \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  يقلل دقة الصور إلى 150 DPI ويحذف المناطق المقصوصة من الصور \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الشرائح الأساسية غير المستخدمة. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة شرائح التخطيط غير المستخدمة. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الأحرف غير المستخدمة من الخطوط المدمجة. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | يقوم بتقليل دقة الصور في العرض التقديمي وحذف المناطق المقصوصة منها، مشابهًا لأداة "Compress Pictures" في PowerPoint المطبقة على جميع الصور. |
### Compress() {#Compress--}
```
public Compress()
```

### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```

يقلل حجم عرض تقديمي عن طريق تطبيق جميع خطوات الضغط المتاحة:

 *  يزيل الشرائح الأساسية غير المستخدمة \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  يزيل شرائح التخطيط غير المستخدمة \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  يحتفظ فقط بالرموز المستخدمة فعليًا في الخطوط المدمجة \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  يقلل دقة الصور إلى 150 DPI ويحذف المناطق المقصوصة من الصور \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المراد ضغطه.

--------------------

لتخصيص الضغط، على سبيل المثال لاستخدام دقة صورة مختلفة أو لتخطي خطوة معينة، استدعِ الأساليب المذكورة أعلاه بشكل فردي بدلاً من هذه الطريقة. يتم حذف المناطق المقصوصة من الصور بشكل دائم ولا يمكن استعادتها في PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الشرائح الأساسية غير المستخدمة.

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | مثيل العرض التقديمي

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة شرائح التخطيط غير المستخدمة.

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | مثيل العرض التقديمي

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الأحرف غير المستخدمة من الخطوط المدمجة.

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | مثيل العرض التقديمي

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

يقوم بتقليل دقة الصور في العرض التقديمي وحذف المناطق المقصوصة منها، مشابهًا لأداة "Compress Pictures" في PowerPoint المطبقة على جميع الصور. يتم معالجة الصور على الشرائح، شرائح التخطيط والشرائح الأساسية، بما في ذلك الصور داخل المجموعات الشكلية وملء الصور للأشكال.

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض التقديمي الذي سيُعالج. |
| resolution | int | دقة الهدف بالنسبة إلى الحجم الذي تُعرض به كل صورة. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) يترك الصور دون تغيير.

الصور التي تكون بالفعل عند الدقة المستهدفة أو أقل تُترك دون تغيير؛ لا يتم تكبير الصور أبدًا.

العناصر غير المعالجة: خلفيات الشرائح، تعبئة خلايا الجداول، الرسوم البيانية، SmartArt، صور GIF (للحفاظ على الحركة)، صور SVG وملفات الميتا (EMF/WMF).

يتم حذف المناطق المقصوصة بشكل دائم ولا يمكن استعادتها في PowerPoint. |
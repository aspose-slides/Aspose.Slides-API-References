---
title: Compress
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الطرق المصممة لضغط .
type: docs
url: /ar/com.aspose.slides/compress/
---
**الوراثة:**
java.lang.Object
```
public class Compress
```

يمثل مجموعة من الطرق المصممة لضغط [Presentation](../../com.aspose.slides/presentation).

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

## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [Compress()](#Compress--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الشرائح الرئيسية غير المستخدمة. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة شرائح التخطيط غير المستخدمة. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الأحرف غير المستخدمة من الخطوط المدمجة. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


يقوم بضغط [Presentation](../../com.aspose.slides/presentation) عن طريق إزالة الشرائح الرئيسية غير المستخدمة.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | مثيل العرض التقديمي |

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | مثيل العرض التقديمي |

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | مثيل العرض التقديمي |
---
title: SlideImageFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد التنسيق الذي سيتم حفظ صورة الشريحة به للتصدير إلى HTML.
type: docs
url: /ar/com.aspose.slides/slideimageformat/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

يحدد التنسيق الذي سيتم حفظ صورة الشريحة به للتصدير إلى HTML.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | يجب تحويل الشرائح إلى تنسيق SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | يجب تحويل الشرائح إلى صورة نقطية. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


يجب تحويل الشرائح إلى تنسيق SVG.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | خيارات تصدير SVG. |

**القيمة المرجعة:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - الكائن [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


يجب تحويل الشرائح إلى صورة نقطية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scale | float | العامل الذي يحدد نسبة تصغير الصورة الناتجة. |
| imageFormat | int | تنسيق الصورة الناتجة (مثال: PNG، JPEG). |

**القيمة المرجعة:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
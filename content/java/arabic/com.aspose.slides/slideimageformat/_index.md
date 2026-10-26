---
title: SlideImageFormat
second_title: Aspose.Slides لمرجع API لجافا
description: يحدد التنسيق الذي ستحفظ به صورة الشريحة عند تصدير العرض التقديمي إلى HTML.
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

يحدد التنسيق الذي ستُحفظ به صورة الشريحة عند تصدير العرض التقديمي إلى HTML.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## الطرق

| الطريقة | الوصف |
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

يجب تحويل الشرائح إلى تنسيق SVG.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | خيارات تصدير SVG. |

**القيم المرجعة:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - كائن [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

يجب تحويل الشرائح إلى صورة نقطية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| scale | float | العامل الذي يتم به تكبير الصورة الناتجة. |
| imageFormat | int | تنسيق الصورة الناتجة (مثل PNG، JPEG). |

**القيم المرجعة:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
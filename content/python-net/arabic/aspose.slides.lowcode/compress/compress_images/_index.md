---
title: compress_images method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
يقوم بتقليل دقة الصور في العرض التقديمي ويحذف المناطق المقصوصة منها، مشابه لـ "Compress Pictures" في PowerPoint المطبقة على جميع الصور. يتم معالجة الصور على الشرائح، شرائح التخطيط والشرائح الرئيسية، بما في ذلك الصور داخل مجموعات الأشكال وتعبئة الصور للأشكال.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation) | العرض التقديمي للمعالجة. |
| resolution | [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression) | دقة الهدف نسبةً إلى الحجم الذي تُعرض به كل صورة.<br/><br/>[`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/ar/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) يترك الصور دون تغيير. |

### ملاحظات

تُترك الصور التي تكون دقتها عند الهدف أو أقل منه دون تغيير؛ لا يتم تكبير الصور أبداً.

غير معالجة: خلفيات الشرائح، تعبئة خلايا الجداول، المخططات، SmartArt، صور GIF (للحفاظ على الرسوم المتحركة)، صور SVG وملفات الميتا (EMF/WMF).

يتم حذف المناطق المقصوصة بشكل دائم ولا يمكن استعادتها في PowerPoint.

### استثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` هو `None`. |

### انظر أيضًا
* فئة [`Compress`](/slides/python-net/ar/aspose.slides.lowcode/compress)
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* تعداد [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression)
* وحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* مكتبة [`Aspose.Slides`](/slides/python-net)
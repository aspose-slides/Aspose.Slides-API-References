---
title: compress_images method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
رزولوشن تصاویر در ارائه را کاهش می‌دهد و نواحی برش خورده آن‌ها را حذف می‌کند، مشابه عملکرد «Compress Pictures» در PowerPoint که بر روی تمام تصاویر اعمال می‌شود. تصاویر در اسلایدها، اسلایدهای چیدمان و اسلایدهای اصلی پردازش می‌شوند، از جمله تصاویر داخل اشکال گروهی و پرکردن تصویر در اشکال.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) | ارائه‌ای که باید پردازش شود. |
| resolution | [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression) | رزولوشن هدف نسبت به اندازه‌ای که هر تصویر نمایش داده می‌شود.<br/><br/>[`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/fa/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) تصاویر را دست‌نخورده می‌گذارد. |

### توضیحات

تصاویری که از پیش در رزولوشن هدف یا کمتر هستند دست‌نخورده باقی می‌مانند؛ تصاویر هرگز بزرگ‌نمایی نمی‌شوند.

مواردی که پردازش نمی‌شوند: پس‌زمینه اسلایدها، پرکردن سلول‌های جدول، نمودارها، SmartArt، تصاویر GIF (برای حفظ انیمیشن)، تصاویر SVG و متافایل (EMF/WMF).

نواحی برش خورده به‌صورت دائم حذف می‌شوند و در PowerPoint قابل بازیابی نیستند.

### استثناها

| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` مقدار `None` است. |

### مراجعه
* کلاس [`Compress`](/slides/python-net/fa/aspose.slides.lowcode/compress)
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* شمارش [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
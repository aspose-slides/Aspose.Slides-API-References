---
title: Compress class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.lowcode/compress/
---
## کلاس Compress

یک گروه از متدها را که برای فشرده‌سازی [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) منظور شده‌اند، نشان می‌دهد.

نوع Compress اعضای زیر را ارائه می‌دهد:

## متدها

| متد | توضیح |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/fa/aspose.slides.lowcode/compress/compress_presentation/#presentation) | اندازه یک ارائه را با اعمال تمام گام‌های فشرده‌سازی موجود کاهش می‌دهد:<br/>            <br/>* اسلایدهای اصلی استفاده نشده را حذف می‌کند **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* اسلایدهای چیدمان استفاده نشده را حذف می‌کند **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* فقط گلیف‌های واقعاً استفاده شده در فونت‌های جاسازی شده را نگه می‌دارد **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* وضوح تصویر را به 150 DPI کاهش می‌دهد و نواحی برش‌خورده تصاویر را حذف می‌کند **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/fa/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | فشرده‌سازی [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) را با حذف اسلایدهای اصلی استفاده نشده انجام می‌دهد. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/fa/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | فشرده‌سازی [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) را با حذف اسلایدهای چیدمان استفاده نشده انجام می‌دهد. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/fa/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | فشرده‌سازی [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) را با حذف کاراکترهای استفاده نشده از فونت‌های جاسازی شده انجام می‌دهد. |
| [`compress_images(presentation, resolution)`](/slides/python-net/fa/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | وضوح تصاویر در ارائه را کاهش می‌دهد و نواحی برش‌خورده آن‌ها را حذف می‌کند،<br/>            مشابه “Compress Pictures” در PowerPoint که بر تمام تصاویر اعمال می‌شود.<br/>            تصاویر بر روی اسلایدها، اسلایدهای چیدمان و اسلایدهای اصلی پردازش می‌شوند، از جمله تصاویری که در داخل شکل‌های گروهی و پرکننده تصویر اشکال قرار دارند. |

### مراجع
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
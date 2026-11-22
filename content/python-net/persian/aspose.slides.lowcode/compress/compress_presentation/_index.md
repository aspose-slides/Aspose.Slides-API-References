---
title: compress_presentation method
second_title: Aspose.Slides برای پایتون از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
اندازه یک ارائه را با اعمال تمام مراحل فشرده‌سازی موجود کاهش می‌دهد:

* اسلایدهای مستر استفاده نشده را حذف می‌کند **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* اسلایدهای چیدمان استفاده نشده را حذف می‌کند **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* فقط گلیف‌های واقعاً استفاده شده در فونت‌های جاسازی‌شده را نگه می‌دارد **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* رزولوشن تصویر را به 150 DPI کاهش می‌دهد و نواحی برش‌خورده تصاویر را حذف می‌کند **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائه‌ای که باید فشرده شود. |

### توضیحات
برای سفارشی‌سازی فشرده‌سازی، به عنوان مثال برای استفاده از رزولوشن تصویر متفاوت یا برای پرهیز از یک مرحله,
            به‌جای این متد، متدهای فهرست‌شده در بالا را به‌صورت جداگانه فراخوانی کنید.
            نواحی برش‌خورده تصاویر به‌صورت دائمی حذف می‌شوند و نمی‌توانند در PowerPoint بازگردانده شوند.

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` است `None`. |



### موارد مرتبط
* کلاس [`Compress`](/slides/python-net/fa/aspose.slides.lowcode/compress)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
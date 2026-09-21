---
title: save_metafiles_as_png property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png ویژگی
True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG.
            خواندن/نوشتن **bool**.


### توضیحات

پیش‌فرض **true** .
            سند Pdf می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. 
            اگر SaveMetafilesAsPng بر روی true تنظیم شود، سپس تصویر منبع Metafile به قالب Png تبدیل شده و به صورت تصویر رستری در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng بر روی false تنظیم شود، سپس Metafile منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر رویکرد مزایا و معایب خود را دارد. به عنوان مثال، اگر Metafile به PNG تبدیل شود، ممکن است در هنگام مقیاس‌گذاری سند نهایی برخی از دست دادن کیفیت رخ دهد. اگر Metafile به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf پیش آید.

### تعریف:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### مراجع
* کلاس [`PdfOptions`](/slides/python-net/fa/aspose.slides.export/pdfoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
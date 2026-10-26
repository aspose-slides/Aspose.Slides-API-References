---
title: save_metafiles_as_png property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png ویژگی
True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG.
            خواندنی/نوشتنی **bool**.

### Remarks
پیش‌فرض **true** .
            سند Pdf می‌تواند گرافیک‌های برداری و تصاویر رستری را شامل شود. 
            اگر SaveMetafilesAsPng به true تنظیم شود، تصویر Metafile منبع به قالب Png تبدیل شده و به‌عنوان تصویر رستری در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng به false تنظیم شود، Metafile منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. به عنوان مثال، اگر Metafile به PNG تبدیل شود، برخی از کاهش کیفیت ممکن است هنگام مقیاس‌بندی سند نهایی رخ دهد. اگر Metafile به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار نمایش Pdf رخ دهد.

### Definition:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### موارد مرتبط
* کلاس [`IPdfOptions`](/slides/python-net/fa/aspose.slides.export/ipdfoptions)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
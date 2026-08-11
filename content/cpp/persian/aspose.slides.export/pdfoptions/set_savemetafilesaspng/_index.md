---
title: set_SaveMetafilesAsPng()
second_title: مرجع API Aspose.Slides برای C++
description: درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. مقدار bool را بنویسید.
type: docs
weight: 339
url: /fa/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) متد


درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. **bool** را بنویسید.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## توضییات


پیش‌فرض **true** است. سند Pdf می‌تواند شامل گرافیک‌های برداری و تصاویر رستر باشد. اگر SaveMetafilesAsPng بر روی **true** تنظیم شود، تصویر Metafile منبع به قالب Png تبدیل شده و به عنوان تصویر رستر در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng بر روی **false** تنظیم شود، Metafile منبع به گرافیک برداری Pdf تبدیل می‌شود. هر رویکرد مزایا و معایب خود را دارد. به عنوان مثال، اگر Metafile به PNG تبدیل شود، در مقیاس‌بندی سند حاصل ممکن است برخی از کیفیت از دست برود. اگر Metafile به گرافیک برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf رخ دهد. 
## مراجع

* کلاس [PdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
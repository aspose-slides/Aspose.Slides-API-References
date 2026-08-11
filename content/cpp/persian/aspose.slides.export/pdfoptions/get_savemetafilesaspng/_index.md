---
title: get_SaveMetafilesAsPng()
second_title: مرجع API Aspose.Slides برای C++
description: True برای تبدیل تمام متافایل‌های استفاده شده در یک ارائه به تصاویر PNG. خواندن bool.
type: docs
weight: 326
url: /fa/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() متد

True برای تبدیل تمام متافایل‌های استفاده شده در یک ارائه به تصاویر PNG. خواندن **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## توضیحات

پیش‌فرض **true** است. سند Pdf می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng روی true تنظیم شود، تصویر منبع Metafile به فرمت Png تبدیل شده و به عنوان تصویر رستری در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng روی false تنظیم شود، Metafile منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر رویکرد مزایا و معایب خود را دارد. به عنوان مثال، اگر Metafile به PNG تبدیل شود، ممکن است در مقیاس‌گذاری سند نهایی مقداری از کیفیت از دست برود. اگر Metafile به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf رخ دهد.

## مراجع

* کلاس [PdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
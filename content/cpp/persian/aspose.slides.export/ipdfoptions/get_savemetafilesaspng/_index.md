---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides برای C++ مرجع API
description: True برای تبدیل تمام متافایل‌های استفاده شده در یک ارائه به تصاویر PNG. خواندن bool.
type: docs
weight: 287
url: /fa/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() متد

True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## توضیحات

پیش‌فرض **true** است. سند Pdf می‌تواند شامل گرافیک‌های برداری و تصاویر شطرنجی باشد. اگر SaveMetafilesAsPng بر روی true تنظیم شود، تصویر Metafile منبع به فرمت Png تبدیل شده و به عنوان تصویر شطرنجی در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng بر روی false تنظیم شود، Metafile منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. برای مثال، اگر Metafile به PNG تبدیل شود، ممکن است در مقیاس‌بندی سند نهایی مقداری کاهش کیفیت رخ دهد. اگر Metafile به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf رخ دهد.

## موارد مربوطه

* کلاس [IPdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides مرجع API برای C++
description: True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. مقدار bool را بنویسید.
type: docs
weight: 300
url: /fa/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) متد


True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## ملاحظات


پیش‌فرض **true** است. سند Pdf می‌تواند شامل گرافیک‌های برداری و تصاویر رستر باشد. اگر SaveMetafilesAsPng برابر **true** باشد، تصویر Metafile منبع به فرمت Png تبدیل شده و به عنوان تصویر رستر در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng برابر **false** باشد، Metafile منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر رویکرد دارای مزایا و معایب است. به عنوان مثال، اگر Metafile به PNG تبدیل شود، ممکن است در مقیاس‌گذاری سند نهایی، برخی از کیفیت‌ها کاهش یابند. اگر Metafile به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf به وجود آید.

## موارد مرتبط

* کلاس [IPdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
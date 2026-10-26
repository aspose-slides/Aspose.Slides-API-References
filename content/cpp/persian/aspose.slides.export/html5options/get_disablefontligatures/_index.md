---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقداری را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. هنگامی که به true تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 131
url: /fa/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() متد

مقداری را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // غیرفعال‌سازی لیگاتورها در رندر متن

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## موارد مرتبط

* کلاس [Html5Options](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
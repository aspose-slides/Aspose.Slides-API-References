---
title: set_DisableFontLigatures()
second_title: مرجع API برای Aspose.Slides در C++
description: مقدار را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 144
url: /fa/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) method

مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. هنگامی که به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به طور پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // غیرفعال کردن لیگچرها در رندر متن

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## موارد مرتبط

* کلاس [Html5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
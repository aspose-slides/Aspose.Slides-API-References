---
title: get_DisableFontLigatures()
second_title: Aspose.Slides برای مرجع API C++
description: یک مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی روی true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی روی false تنظیم شده است.
type: docs
weight: 131
url: /fa/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() متد

یک مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی روی **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی روی **false** تنظیم شده است.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
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

* کلاس [IHtml5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
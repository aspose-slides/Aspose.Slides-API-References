---
title: set_DisableFontLigatures()
second_title: Aspose.Slides برای مرجع API C++
description: یک مقدار را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. هنگامی که به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی false تنظیم شده است.
type: docs
weight: 144
url: /fa/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) متد


یک مقدار را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر شود. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی **false** تنظیم شده است.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // غیرفعال کردن لیگچرها در رندر متن

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## مراجع

* کلاس [IHtml5Options](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
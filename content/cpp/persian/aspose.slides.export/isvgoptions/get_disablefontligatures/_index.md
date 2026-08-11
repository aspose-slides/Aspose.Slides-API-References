---
title: get_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقداری را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌صورت پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 326
url: /fa/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() متد


یک مقدار را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال خواهند شد. به‌صورت پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // غیرفعال‌سازی لیگچرها در رندر متن

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## موارد مرتبط

* کلاس [ISVGOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
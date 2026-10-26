---
title: set_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقدارى را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجى رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 339
url: /fa/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) متد

مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
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
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
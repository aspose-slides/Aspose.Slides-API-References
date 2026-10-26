---
title: set_DisableFontLigatures()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگیچرها رندر می‌شود. وقتی به true تنظیم شود، لیگیچرها در خروجی رندر شده غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی به false تنظیم شده است.
type: docs
weight: 339
url: /fa/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) متد


مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگیچرها رندر می‌شود. هنگامی که **true** تنظیم شود، لیگیچرها در خروجی رندر شده غیرفعال خواهند شد. به‌طور پیش‌فرض، این ویژگی به **false** تنظیم شده است.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // غیرفعال کردن لیگیچرها در رندر متن

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## موارد مرتبط

* کلاس [SVGOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)
---
title: set_Password()
second_title: Aspose.Slides برای مرجع API C++
description: "کلمه‌عبور را تنظیم می‌کند. System::String را بنویسید."
type: docs
weight: 118
url: /fa/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) متد

کلمه‌عبور را تنظیم می‌کند. [System::String](../../../system/string/) را بنویسید.

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## توضیحات

کلمه‌عبور.

کد نمونه زیر نشان می‌دهد که چگونه PowerPoint [Presentation](../../presentation/) محافظت‌شده با کلمه‌عبور را باز کنید.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// کار با ارائهٔ رمزگشایی‌شده
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
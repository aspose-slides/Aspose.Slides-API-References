---
title: get_Password()
second_title: مرجع API Aspose.Slides برای C++
description: "کلمه‌عبور را دریافت می‌کند. بخوانید System::String."
type: docs
weight: 105
url: /fa/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() متد


کلمه‌عبور را دریافت می‌کند. بخوانید [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## توضییات


کلمه‌عبور. 

کد نمونه زیر نشان می‌دهد چگونه یک PowerPoint محافظت‌شده با کلمه‌عبور را باز کنید [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [LoadOptions](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
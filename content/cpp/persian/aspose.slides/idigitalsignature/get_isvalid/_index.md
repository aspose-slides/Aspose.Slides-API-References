---
title: get_IsValid()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار درست خواهد بود. فقط‌خواندنی bool.
type: docs
weight: 14
url: /fa/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() متد

اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار درست خواهد بود. فقط‌خواندنی **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## موارد مرتبط

* کلاس [IDigitalSignature](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
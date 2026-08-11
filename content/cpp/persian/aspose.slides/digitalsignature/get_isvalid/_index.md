---
title: get_IsValid()
second_title: Aspose.Slides برای مرجع API C++
description: اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار true خواهد بود. فقط-خواندنی bool.
type: docs
weight: 14
url: /fa/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() متد


اگر این امضای دیجیتال معتبر باشد و سند دستکاری نشده باشد، این مقدار true خواهد بود. فقط-خواندنی **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

* کلاس [DigitalSignature](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
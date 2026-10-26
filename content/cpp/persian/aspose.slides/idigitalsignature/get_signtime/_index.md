---
title: get_SignTime()
second_title: مرجع API Aspose.Slides برای C++
description: "زمانی که سند امضا شد. فقط-خواندنی System::DateTime."
type: docs
weight: 27
url: /fa/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() متد

زمانی که سند امضا شد. فقط-خواندنی [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## موارد مرتبط

* کلاس [DateTime](../../../system/datetime/)
* کلاس [IDigitalSignature](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
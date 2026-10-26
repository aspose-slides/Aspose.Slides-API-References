---
title: get_SignTime()
second_title: مرجع API Aspose.Slides برای C++
description: "زمانی که سند امضا شد. فقط خواندنی System::DateTime."
type: docs
weight: 27
url: /fa/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() متد


زمانی که سند امضا شده است. فقط خواندنی [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## مراجعه شود به

* کلاس [DateTime](../../../system/datetime/)
* کلاس [DigitalSignature](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)
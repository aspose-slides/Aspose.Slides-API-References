---
title: get_SignTime()
second_title: Aspose.Slides för C++ API-referens
description: "Tiden då dokumentet undertecknades. Skrivskyddad System::DateTime."
type: docs
weight: 27
url: /sv/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() metod


Tiden då dokumentet undertecknades. Skrivskyddad [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Se också

* Klass [DateTime](../../../system/datetime/)
* Klass [IDigitalSignature](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
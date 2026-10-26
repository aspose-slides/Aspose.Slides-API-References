---
title: get_IsValid()
second_title: Aspose.Slides för C++ API-referens
description: Om denna digitala signatur är giltig och dokumentet inte har manipulerats, kommer detta värde att vara sant. Skrivskyddad bool.
type: docs
weight: 14
url: /sv/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() metod


Om denna digitala signatur är giltig och dokumentet inte har manipulerats, kommer detta värde att vara sant. Skrivskyddad **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Se också

* Klass [DigitalSignature](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
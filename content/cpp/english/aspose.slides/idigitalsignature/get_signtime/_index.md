---
title: get_SignTime()
second_title: Aspose.Slides for C++ API Reference
description: "The time when the document was signed. Read-only System::DateTime."
type: docs
weight: 27
url: /aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() method


The time when the document was signed. Read-only [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## See Also

* Class [DateTime](../../../system/datetime/)
* Class [IDigitalSignature](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
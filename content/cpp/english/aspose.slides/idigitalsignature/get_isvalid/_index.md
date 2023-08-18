---
title: get_IsValid()
second_title: Aspose.Slides for C++ API Reference
description: If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only bool.
type: docs
weight: 14
url: /aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() method


If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## See Also

* Class [IDigitalSignature](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
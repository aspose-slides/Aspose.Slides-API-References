---
title: get_SignTime()
second_title: Aspose.Slides for C++ API Reference
description: "The time when the document was signed. Read-only System::DateTime."
type: docs
weight: 27
url: /cpp/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() method


The time when the document was signed. Read-only [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Remarks



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

## See Also

* Class [DateTime](../../../system/datetime/)
* Class [DigitalSignature](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: get_DigitalSignatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de verzameling handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen IDigitalSignatureCollection.
type: docs
weight: 261
url: /nl/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() methode


Retourneert de verzameling handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;

    System::Console::WriteLine(u"Signatures used to sign the presentation: ");

    for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
    {
        auto signature = pres->get_DigitalSignatures()->idx_get(i);
        System::Console::WriteLine(u"{0}, {1} --- {2}",
            signature->get_Certificate()->get_SubjectName()->get_Name(),
            signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm"),
            (signature->get_IsValid() ? u"VALID" : u"INVALID")
        );
        allSignaturesAreValid &= signature->get_IsValid();
    }
}
@verbatim 
if (allSignaturesAreValid)
    System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
else
    System::Console::WriteLine(u"Presentation has been modified since signing.");
@endverbatim }
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
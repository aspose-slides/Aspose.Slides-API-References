---
title: get_DigitalSignatures()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad IDigitalSignatureCollection.
type: docs
weight: 261
url: /sv/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() metod


Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## Anmärkningar



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

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
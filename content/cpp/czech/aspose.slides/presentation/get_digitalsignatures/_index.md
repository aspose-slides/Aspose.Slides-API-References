---
title: get_DigitalSignatures()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací kolekci podpisů použitých k podepsání prezentace. Pouze ke čtení IDigitalSignatureCollection.
type: docs
weight: 261
url: /cs/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() metoda


Vrací kolekci podpisů použitých k podepsání prezentace. Pouze ke čtení [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## Poznámky



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

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
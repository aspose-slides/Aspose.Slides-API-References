---
title: get_DigitalSignatures()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací kolekci podpisů používaných k podepsání prezentace. Pouze pro čtení IDigitalSignatureCollection.
type: docs
weight: 378
url: /cs/aspose.slides/ipresentation/get_digitalsignatures/
---
## IPresentation::get_DigitalSignatures() method


Vrací kolekci podpisů používaných k podepsání prezentace. Pouze ke čtení [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
virtual System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::IPresentation::get_DigitalSignatures()=0
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

    if (allSignaturesAreValid)
        System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
    else
        System::Console::WriteLine(u"Presentation has been modified since signing.");
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* Třída [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)
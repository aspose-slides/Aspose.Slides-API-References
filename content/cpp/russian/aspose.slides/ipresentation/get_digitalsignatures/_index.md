---
title: get_DigitalSignatures()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает коллекцию подписей, используемых для подписи презентации. Только для чтения IDigitalSignatureCollection.
type: docs
weight: 378
url: /ru/aspose.slides/ipresentation/get_digitalsignatures/
---
## IPresentation::get_DigitalSignatures() метод


Возвращает коллекцию подписей, используемых для подписи презентации. Только для чтения [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
virtual System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::IPresentation::get_DigitalSignatures()=0
```

## Примечания



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

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* Класс [IPresentation](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
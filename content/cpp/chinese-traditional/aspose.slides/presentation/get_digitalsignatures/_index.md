---
title: get_DigitalSignatures()
second_title: Aspose.Slides C++ API 參考
description: 傳回用於簽署簡報的簽章集合。唯讀 IDigitalSignatureCollection.
type: docs
weight: 261
url: /zh-hant/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() 方法

傳回用於簽署簡報的簽章集合。唯讀 [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## 備註


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

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
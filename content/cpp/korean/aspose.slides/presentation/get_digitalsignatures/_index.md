---
title: get_DigitalSignatures()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 서명하는 데 사용된 서명 컬렉션을 반환합니다. 읽기 전용 IDigitalSignatureCollection.
type: docs
weight: 261
url: /ko/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() 메서드


프레젠테이션에 서명하는 데 사용된 서명 컬렉션을 반환합니다. 읽기 전용 [IDigitalSignatureCollection](../../idigitalsignaturecollection/).

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## 비고



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

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
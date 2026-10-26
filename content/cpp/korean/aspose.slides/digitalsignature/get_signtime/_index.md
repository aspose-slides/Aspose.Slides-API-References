---
title: get_SignTime()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "문서가 서명된 시간입니다. 읽기 전용 System::DateTime."
type: docs
weight: 27
url: /ko/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() 메서드

문서가 서명된 시간입니다. 읽기 전용 [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## 비고

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

## 관련 항목

* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [DigitalSignature](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
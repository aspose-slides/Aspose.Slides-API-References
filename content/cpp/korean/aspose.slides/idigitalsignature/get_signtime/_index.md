---
title: get_SignTime()
second_title: Aspose.Slides for C++ API 참조
description: "문서가 서명된 시각입니다. 읽기 전용 System::DateTime."
type: docs
weight: 27
url: /ko/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() 메서드

문서가 서명된 시각입니다. 읽기 전용 [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## 비고


```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## 참조
* 클래스 [DateTime](../../../system/datetime/)
* 클래스 [IDigitalSignature](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
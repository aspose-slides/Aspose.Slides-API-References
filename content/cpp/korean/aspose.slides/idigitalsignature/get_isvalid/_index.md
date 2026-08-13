---
title: get_IsValid()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 디지털 서명이 유효하고 문서가 변조되지 않은 경우, 이 값은 true가 됩니다. 읽기 전용 bool.
type: docs
weight: 14
url: /ko/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() 메서드


이 디지털 서명이 유효하고 문서가 변조되지 않은 경우, 이 값은 true가 됩니다. 읽기 전용 **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## 또 보기

* 클래스 [IDigitalSignature](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: get_IsValid()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 디지털 서명이 유효하고 문서가 변조되지 않았으면 이 값은 true가 됩니다. 읽기 전용 bool.
type: docs
weight: 14
url: /ko/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() 메서드


If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

## 참조

* 클래스 [DigitalSignature](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
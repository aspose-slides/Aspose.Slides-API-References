---
title: set_Password()
second_title: Aspose.Slides C++ API 레퍼런스
description: "비밀번호를 설정합니다. System::String을 작성합니다."
type: docs
weight: 118
url: /ko/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) 메서드

비밀번호를 설정합니다. 작성하십시오 [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## 참고

비밀번호.

다음 샘플 코드는 비밀번호가 보호된 PowerPoint [Presentation](../../presentation/)를 여는 방법을 보여줍니다.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
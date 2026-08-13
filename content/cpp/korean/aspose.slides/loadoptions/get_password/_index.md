---
title: get_Password()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "비밀번호를 가져옵니다. System::String을 읽으십시오."
type: docs
weight: 105
url: /ko/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() 메서드

비밀번호를 가져옵니다. [System::String](../../../system/string/)를 읽으십시오.

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## 비고

비밀번호.

다음 예제 코드는 암호로 보호된 PowerPoint [Presentation](../../presentation/)를 여는 방법을 보여 줍니다.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
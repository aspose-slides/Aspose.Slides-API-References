---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바인드된 프레젠테이션이 열기 위해 비밀번호로 보호되는지 여부를 나타내는 값을 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() 메서드


바인드된 프레젠테이션이 열기 위해 비밀번호로 보호되는지 여부를 나타내는 값을 가져옵니다.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## 비고



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## 참조

* 클래스 [PresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
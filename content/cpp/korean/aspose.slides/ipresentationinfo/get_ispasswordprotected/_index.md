---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바인드된 프레젠테이션이 열기 위해 비밀번호로 보호되는지 여부를 나타내는 값을 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() 메서드

바인드된 프레젠테이션이 열기 위해 비밀번호로 보호되는지 여부를 나타내는 값을 가져옵니다.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## 비고



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## 참고

* 클래스 [IPresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
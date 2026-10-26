---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바인드된 프레젠테이션이 쓰기 보호되어 있는지를 나타내는 값을 가져옵니다.
type: docs
weight: 27
url: /ko/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() 메서드

바인드된 프레젠테이션이 쓰기 보호되어 있는지를 나타내는 값을 가져옵니다.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## 비고

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

프레젠테이션이 열기 비밀번호로 보호된 경우, 속성 값은 NotDefined와 같습니다.

## 참고

* 열거형 [NullableBool](../../nullablebool/)
* 클래스 [PresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
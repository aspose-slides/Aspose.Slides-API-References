---
title: get_IsWriteProtected()
second_title: Aspose.Slides for C++ API 참조
description: 바인딩된 프리젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 가져옵니다.
type: docs
weight: 27
url: /ko/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() 메서드


바인딩된 프리젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 가져옵니다.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## 비고



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


프리젠테이션이 열기 비밀번호로 보호된 경우, 속성 값은 NotDefined와 같습니다. [NullableBool](../../nullablebool/) 열거형을 참조하십시오. 
## 참고

* 열거형 [NullableBool](../../nullablebool/)
* 클래스 [IPresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
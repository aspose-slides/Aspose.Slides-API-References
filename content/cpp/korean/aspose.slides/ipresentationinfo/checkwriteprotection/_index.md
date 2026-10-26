---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 쓰기 보호된 프레젠테이션에 대한 수정 비밀번호가 올바른지 확인합니다.
type: docs
weight: 66
url: /ko/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) 메서드

수정용 비밀번호가 쓰기 보호된 프레젠테이션에 대해 올바른지 확인합니다.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 확인할 비밀번호입니다. |

### 반환값

프레젠테이션이 쓰기 보호되어 있고 비밀번호가 올바른 경우 true를 반환합니다. 그렇지 않으면 false를 반환합니다.

## 비고

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. 이 메서드를 호출하기 전에 [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) 속성을 확인해야 합니다.
1. 비밀번호가 null이거나 비어 있으면 이 메서드는 false를 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IPresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
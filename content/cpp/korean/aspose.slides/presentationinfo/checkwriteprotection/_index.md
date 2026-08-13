---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 참조
description: 쓰기 보호된 프레젠테이션에 대한 수정 비밀번호가 올바른지 확인합니다.
type: docs
weight: 66
url: /ko/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) 메서드

쓰기 보호된 프레젠테이션에 대한 수정 비밀번호가 올바른지 확인합니다.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 확인할 비밀번호입니다. |

### 반환 값

프레젠테이션이 쓰기 보호되고 비밀번호가 올바른 경우 True를 반환합니다. 그렇지 않으면 False를 반환합니다.

## 비고

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. 이 메서드를 호출하기 전에 [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) 속성을 확인해야 합니다.
1. 비밀번호가 null이거나 비어 있는 경우, 이 메서드는 false를 반환합니다.

## 또 보기

* 클래스 [String](../../../system/string/)
* 클래스 [PresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
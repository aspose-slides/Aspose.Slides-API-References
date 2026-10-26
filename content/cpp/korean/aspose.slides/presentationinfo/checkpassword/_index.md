---
title: CheckPassword()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션이 개방 암호로 보호된 경우 비밀번호가 올바른지 확인합니다.
type: docs
weight: 53
url: /ko/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) 메서드

프레젠테이션이 개방 암호로 보호된 경우 비밀번호가 올바른지 확인합니다.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 확인할 비밀번호입니다. |

### 리턴 값

프레젠테이션이 개방 암호로 보호되고 비밀번호가 올바른 경우 true를 반환하고, 그 외의 경우 false를 반환합니다.

## 비고

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

비밀번호가 null이거나 비어 있으면 이 메서드는 false를 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [PresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
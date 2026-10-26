---
title: CheckPassword()
second_title: Aspose.Slides for C++ API 참조
description: 오픈 비밀번호로 보호된 프레젠테이션에 대해 비밀번호가 올바른지 확인합니다.
type: docs
weight: 53
url: /ko/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) 메서드

presentation이 open password로 보호된 경우 비밀번호가 올바른지 확인합니다.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 확인할 비밀번호입니다. |

### 반환값

프레젠테이션이 open password로 보호되어 있고 비밀번호가 올바른 경우 true, 그렇지 않은 경우 false를 반환합니다.

## 비고

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

비밀번호가 null이거나 빈 문자열인 경우, 이 메서드는 false를 반환합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IPresentationInfo](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
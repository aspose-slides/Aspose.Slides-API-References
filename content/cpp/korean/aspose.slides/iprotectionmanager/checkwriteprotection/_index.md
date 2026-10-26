---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션이 수정하기 위해 비밀번호로 보호되어 있는지 여부를 판단합니다.
type: docs
weight: 157
url: /ko/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) 메서드

Determines whether a presentation is a password protected to modify.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 확인용 비밀번호. |

### 반환 값

True if the password is valid; otherwise, false.

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. 이 메서드를 호출하기 전에 [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) 속성을 확인해야 합니다.
1. 비밀번호가 null이거나 비어있을 경우, 이 메서드는 false를 반환합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
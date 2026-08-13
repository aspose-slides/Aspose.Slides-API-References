---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션이 수정에 대해 암호로 보호되어 있는지 여부를 결정합니다.
type: docs
weight: 157
url: /ko/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) 메서드


프레젠테이션이 수정에 대해 암호로 보호되어 있는지 여부를 결정합니다.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 확인을 위한 password. |

### 반환 값

password가 유효하면 True; 그렇지 않으면 false.
## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. 이 메서드를 호출하기 전에 [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) 속성을 확인해야 합니다.
1. password가 null이거나 비어 있는 경우, 이 메서드는 false를 반환합니다.


## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [ProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
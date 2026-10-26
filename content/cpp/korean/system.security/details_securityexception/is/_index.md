---
title: Is()
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 27
url: /ko/system.security/details_securityexception/is/
---
## Details_SecurityException::Is(const System::TypeInfo\&) const 메서드




```cpp
bool System::Security::Details_SecurityException::Is(const System::TypeInfo &target) const override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 구조는 현재 객체를 테스트할 유형을 설명합니다. |

### 반환 값

True if object is of tagged type or its subclass, false otherwise.

## 비고

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## 참조

* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [Details_SecurityException](../)
* 네임스페이스 [System::Security](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system.security.authentication/details_authenticationexception/is/
---
## Details_AuthenticationException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Security::Authentication::Details_AuthenticationException::Is(const System::TypeInfo &target) const override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 구조체는 현재 객체를 테스트할 타입을 설명합니다. |

### 반환값

객체가 지정된 타입이거나 해당 타입의 서브클래스인 경우 true, 그렇지 않으면 false.

## 비고

객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C#의 'is' 연산자와 유사합니다.

## 참고

* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [Details_AuthenticationException](../)
* 네임스페이스 [System::Security::Authentication](../../)
* 라이브러리 [Aspose.Slides](../../../)
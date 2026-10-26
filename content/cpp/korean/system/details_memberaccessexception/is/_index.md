---
title: Is()
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 27
url: /ko/system/details_memberaccessexception/is/
---
## 세부 정보_MemberAccessException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_MemberAccessException::Is(const System::TypeInfo &target) const override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 구조체는 현재 객체를 테스트할 유형을 설명합니다. |

### 반환 값

객체가 지정된 유형이거나 그 하위 클래스인 경우 true, 그렇지 않으면 false.

## 비고

객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다.

## 참조

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Details_MemberAccessException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
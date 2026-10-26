---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system/details_argumentnullexception/is/
---
## 세부 정보_ArgumentNullException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArgumentNullException::Is(const System::TypeInfo &target) const override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 구조는 현재 객체를 테스트할 대상 유형을 설명합니다. |

### 반환 값

객체가 지정된 유형 또는 그 하위 클래스인 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.

## 비고

객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C#의 'is' 연산자와 동일합니다.

## 관련 항목

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Details_ArgumentNullException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
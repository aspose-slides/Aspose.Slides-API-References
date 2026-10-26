---
title: Is()
second_title: Aspose.Slides C++ API 참조
description: 
type: docs
weight: 27
url: /ko/system.io/details_invaliddataexception/is/
---
## Details_InvalidDataException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_InvalidDataException::Is(const System::TypeInfo &target) const override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 구조체는 현재 객체를 검사할 타입을 설명합니다. |

### 반환값

객체가 지정된 타입 또는 그 하위 클래스인 경우 true, 그렇지 않으면 false.

## 비고

객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C#의 'is' 연산자와 유사합니다.

## 참조

* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [Details_InvalidDataException](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)
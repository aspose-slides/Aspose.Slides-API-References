---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system/details_arithmeticexception/is/
---
## 세부정보_ArithmeticException::Is(const System::TypeInfo\&) const 메서드




```cpp
bool System::Details_ArithmeticException::Is(const System::TypeInfo &target) const override
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 구조체는 현재 객체를 테스트할 유형을 설명합니다. |

### 반환값

True if object is of tagged type or its subclass, false otherwise.

## 비고

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

## 관련 항목

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Details_ArithmeticException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
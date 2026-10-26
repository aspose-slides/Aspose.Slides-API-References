---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system/details_stackoverflowexception/is/
---
## Details_StackOverflowException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_StackOverflowException::Is(const System::TypeInfo &target) const override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 현재 객체가 테스트할 유형을 설명하는 구조체. |

### 반환값

태그가 지정된 유형이나 해당 하위 클래스인 경우 true, 그렇지 않으면 false.

## 비고

객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다.

## 참조

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Details_StackOverflowException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
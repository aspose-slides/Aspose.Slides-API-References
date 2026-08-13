---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system/details_notsupportedexception/is/
---
## Details_NotSupportedException::Is(const System::TypeInfo\&) const 메서드

```cpp
bool System::Details_NotSupportedException::Is(const System::TypeInfo &target) const override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 구조는 현재 객체를 테스트할 대상 유형을 설명합니다. |

### 반환 값

True if object is of tagged type or its subclass, false otherwise.

## 비고

객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 동일합니다.

## 또 보기

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Details_NotSupportedException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
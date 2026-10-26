---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system/details_notimplementedexception/is/
---
## Details_NotImplementedException::Is(const System::TypeInfo\&) const 메서드




```cpp
bool System::Details_NotImplementedException::Is(const System::TypeInfo &target) const override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 구조체로, 현재 객체와 비교할 타입을 설명합니다. |

### 반환 값

객체가 태그된 타입이거나 그 하위 클래스인 경우 True, 그렇지 않으면 false.

## 비고

객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다.

## 참조

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Details_NotImplementedException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
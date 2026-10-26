---
title: Is()
second_title: Aspose.Slides for C++ API 참조
description: 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다.
type: docs
weight: 222
url: /ko/system/object/is/
---
## Object::Is(const TypeInfo\&) const 메서드

객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다.

```cpp
virtual bool System::Object::Is(const TypeInfo &targetType) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetType | const [TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 구조는 현재 객체를 테스트할 타입을 설명합니다. |

### 반환 값

객체가 태그된 타입 또는 그 하위 클래스인 경우 true, 그렇지 않으면 false.

## 참조

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [Object](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
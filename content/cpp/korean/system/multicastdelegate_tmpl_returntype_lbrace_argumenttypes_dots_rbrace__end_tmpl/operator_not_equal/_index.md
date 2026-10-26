---
title: operator!=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 델리게이트 컬렉션이 비어 있지 않은지 여부를 결정합니다.
type: docs
weight: 131
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_not_equal/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator!=(const std::nullptr_t\&) const method

델리게이트 컬렉션이 비어 있지 않은지 여부를 결정합니다.

```cpp
bool System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator!=(const std::nullptr_t &) const
```

### 반환 값

델리게이트 컬렉션이 비어 있지 않으면 True, 그렇지 않으면 - false

## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator!=(const MulticastDelegate\&) const method

두 개의 MulticastDelegate 인스턴스(현재 객체와 지정된 객체)가 서로 다른지 여부를 결정합니다.

```cpp
bool System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator!=(const MulticastDelegate &other) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [MulticastDelegate](../multicastdelegate/)\& | 비교할 MulticastDelegate 객체 |

### 반환 값

두 객체가 동일한 delegate 컬렉션을 나타내면 True, 그렇지 않으면 - false

## 참고

* 메서드 [MulticastDelegate](../multicastdelegate/)
* 클래스 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
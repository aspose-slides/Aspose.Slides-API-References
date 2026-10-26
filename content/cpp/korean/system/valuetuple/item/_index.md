---
title: Item()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ValueTuple 객체의 구성 요소 값에 대한 참조를 반환합니다.
type: docs
weight: 14
url: /ko/system/valuetuple/item/
---
## ValueTuple::Item() 메서드

[ValueTuple](../) 객체의 구성 요소 값에 대한 참조를 반환합니다.

```cpp
template<std::size_t> std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Index | 클래스가 반환해야 하는 항목 번호. |

## ValueTuple::Item() const 메서드

[ValueTuple](../) 객체의 구성 요소 값을 반환합니다.

```cpp
template<std::size_t> const std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item() const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Index | 클래스가 반환해야 하는 항목 번호. |

## 참고

* 클래스 [Index](../../index/)
* 클래스 [ValueTuple](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)
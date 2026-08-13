---
title: ValueTuple
second_title: Aspose.Slides for C++ API 레퍼런스
description: ValueTuple 데이터 구조를 나타내는 클래스입니다.
type: docs
weight: 1444
url: /ko/system/valuetuple/
---
## ValueTuple 클래스

[ValueTuple](./) 데이터 구조를 나타내는 클래스입니다.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | 현재 객체와 지정된 객체가 동일한지 판단합니다. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | [ValueTuple](./) 객체 구성 요소의 값에 대한 참조를 가져옵니다. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | [ValueTuple](./) 객체 구성 요소의 값을 가져옵니다. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 객체를 이 값 튜플로 분해합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [ValueTuple](./) 클래스 형식 정보를 나타내는 [TypeInfo](../typeinfo/) 객체에 대한 참조를 반환합니다. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | 튜플 객체를 생성합니다. |

## 또한 보기

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
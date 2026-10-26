---
title: Nullable
second_title: Aspose.Slides for C++ API 참조
description: 전방 선언.
type: docs
weight: 1106
url: /ko/system/nullable/
---
## Nullable 클래스

Forward declaration.

```cpp
template<typename T>class Nullable
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 기본 값 유형으로, [Nullable](./) 클래스에 의해 확장됩니다. |

## Methods

| 메서드 | 설명 |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값과 같은지 확인합니다. |
| **bool** [get_HasValue](./get_hasvalue/)() const | 현재 객체가 어떤 값을 나타내는지 확인합니다. |
| T [get_Value](./get_value/)() const | 현재 객체가 나타내는 값의 복사본을 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체의 해시 코드를 반환합니다. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | 현재 객체가 나타내는 값 또는 현재 객체가 null인 경우 지정된 값을 반환합니다. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | 현재 객체가 null값을 나타내는지 확인합니다. |
| [Nullable](./nullable/)() | null값을 나타내는 인스턴스를 생성합니다. |
| [Nullable](./nullable/)(std::nullptr_t) | null을 나타내는 인스턴스를 생성합니다. |
| [Nullable](./nullable/)(const T1\&) | [Nullable](./) 클래스를 인스턴스화하여 지정된 값을 기본 유형 T의 값으로 변환(필요한 경우)하여 나타냅니다. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | 지정된 [Nullable](./) 객체가 나타내는 값을 나타내는 인스턴스를 생성합니다. 지정된 nullable 객체가 생성된 인스턴스의 기본 유형과 다른 유형의 값을 나타낼 수 있으며, 이 경우 나타낸 값이 유형 T의 값으로 변환됩니다. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | this와 **other**가 모두 null이 아니며 그 경우 람다를 호출하는지 확인하는 도우미 함수입니다. 구현에 사용됩니다. |
| [operator const T &](./operator_const_t__and/)() const | 현재 객체가 나타내는 값에 대한 const 참조를 반환합니다. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 현재 객체가 나타내는 값이 null이 아닌지 확인합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 값과 같지 않은지 확인합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값과 같지 않은지 확인합니다. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | 지정된 값을 오른쪽 인자로 사용하여 [operator&=()](./operator_and_equal/)를 현재 객체가 나타내는 값에 적용합니다. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Nullable<T> 클래스의 기본 생성 인스턴스를 반환합니다. |
| auto [operator+](./operator_plus/)(const T1\&) const | nullable 값과 non-nullable 값을 합산합니다. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | nullable 값을 합산합니다. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | 현재 객체를 재설정하여 null값을 나타내게 합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | 지정된 값을 오른쪽 인자로 사용하여 [operator+=()](./operator_plus_equal/)를 현재 객체가 나타내는 값에 적용합니다. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | 지정된 [Nullable](./) 객체가 나타내는 값을 오른쪽 인자로 사용하여 [operator+=()](./operator_plus_equal/)를 현재 객체가 나타내는 값에 적용합니다. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | nullable 값과 null 포인터 값을 뺍니다. |
| auto [operator-](./operator_minus/)(const T1\&) const | nullable 값과 non-nullable 값을 뺍니다. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | nullable 값을 뺍니다. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | null값을 나타내는 [Nullable](./) 클래스의 인스턴스를 반환합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | 지정된 값을 오른쪽 인자로 사용하여 [operator-=()](./operator_minus_equal/)를 현재 객체가 나타내는 값에 적용합니다. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | 지정된 [Nullable](./) 객체가 나타내는 값을 오른쪽 인자로 사용하여 [operator-=()](./operator_minus_equal/)를 현재 객체가 나타내는 값에 적용합니다. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 값보다 작으며, 이를 위해 [operator<()](./operator_less/)를 적용하는지 확인합니다. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값보다 작으며, 이를 위해 [operator<()](./operator_less/)를 적용하는지 확인합니다. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 값보다 작거나 같으며, 이를 위해 [operator<=()](./operator_less_equal/)를 적용하는지 확인합니다. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값보다 작거나 같은지, 이를 위해 [operator<=()](./operator_less_equal/)를 적용하는지 확인합니다. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | 현재 객체에 null을 할당합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | 객체가 현재 나타내는 값을 지정된 값으로 교체합니다. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | 객체가 현재 나타내는 값을 지정된 값으로 교체합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 현재 객체가 나타내는 값이 null인지 확인합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 값과 같은지 확인합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값과 같은지 확인합니다. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 값보다 크며, 이를 위해 [operator>()](./operator_greater/)를 적용하는지 확인합니다. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값보다 크며, 이를 위해 [operator>()](./operator_greater/)를 적용하는지 확인합니다. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | 현재 객체가 나타내는 값이 지정된 객체가 나타내는 값보다 크거나 같으며, 이를 위해 [operator>=()](./operator_greater_equal/)를 적용하는지 확인합니다. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | 현재 객체가 나타내는 값이 지정된 [Nullable](./) 객체가 나타내는 값보다 크거나 같으며, 이를 위해 [operator>=()](./operator_greater_equal/)를 적용하는지 확인합니다. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | 지정된 값을 오른쪽 인자로 사용하여 [operator|=()](./operator_or_equal/)를 현재 객체가 나타내는 값에 적용합니다. |
| void [reset](./reset/)() | 현재 나타내는 값을 null로 설정합니다. |
| void [set_Value](./set_value/)(const T\&) | nullable 객체에 새 값을 설정합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 값을 문자열로 변환합니다. |

## Typedefs

| 타입 별칭 | 설명 |
| --- | --- |
| [ValueType](./valuetype/) | 이 클래스가 나타내는 값 유형에 대한 별칭입니다. |

## 비고

지정된 유형의 값을 나타내며 null을 할당할 수 있습니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

## 또한 보기

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)
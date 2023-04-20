---
title: operator-()
second_title: Aspose.Slides for C++ API Reference
description: Subtracts nullable and null-pointed values.
type: docs
weight: 209
url: /cpp/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const method


Subtracts nullable and null-pointed values.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Right operand type, should be nullptr_t. |

### Return Value

Empty [Nullable](../) object.

## Nullable::operator-(const T1\&) const method


Subtracts nullable and non-nullable values.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Right operand type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | value to subtract. |

### Return Value

Subtraction result.

## Nullable::operator-(const Nullable\<T1\>\&) const method


Subtracts nullable values.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Right operand type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | value to subtract. |

### Return Value

Subtraction result.

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
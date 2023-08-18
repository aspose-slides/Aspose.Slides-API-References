---
title: operator+()
second_title: Aspose.Slides for C++ API Reference
description: Returns a default constructed instance of Nullable<T> class.
type: docs
weight: 196
url: /system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const method


Returns a default constructed instance of Nullable<T> class.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const method


Sums nullable and non-nullable values.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Right operand type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | value to add. |

### Return Value

Summing result.

## Nullable::operator+(const Nullable\<T1\>\&) const method


Sums nullable values.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Right operand type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | value to add. |

### Return Value

Summing result.

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
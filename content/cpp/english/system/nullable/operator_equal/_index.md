---
title: operator=()
second_title: Aspose.Slides for C++ API Reference
description: Assigns a null to the current object.
type: docs
weight: 14
url: /system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) method


Assigns a null to the current object.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Return Value

A [Nullable](../) object that represents null-value.

## Nullable::operator=(const T1\&) method


Replaces the object's currently represented value with the specified one.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the new value to be represented by the current object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T1\& | The new value to be represented by the current object |

### Return Value

A reference to the self

## Nullable::operator=(const Nullable\<T1\>\&) method


Replaces the object's currently represented value with the specified one.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the new value to be represented by the current object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | The new value to be represented by the current object |

### Return Value

A reference to the self

## See Also

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
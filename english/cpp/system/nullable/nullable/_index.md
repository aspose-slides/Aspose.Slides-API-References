---
title: Nullable()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance that represents null-value.
type: docs
weight: 1
url: /cpp/system/nullable/nullable/
---
## Nullable::Nullable() constructor


Constructs an instance that represents null-value.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) constructor


Constructs an instance that represents null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) constructor


Constructs an instance of [Nullable](../) class that represents the specified value converted (if necessary) to the value of the underlying type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The type of the specified value |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T1\& | A constant reference to the value to be represented by the newly constructed [Nullable](../) object |

## Nullable::Nullable(const Nullable\<T1\>\&) constructor


Constructs an instance that represents a value that is represented by the specified [Nullable](../) object. The specified nullable object may represent a value of different type than the underlying type of the constructed instance in which case the represented value is converted to a value of type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The type of the value represented by the specified [Nullable](../) object |

## See Also

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
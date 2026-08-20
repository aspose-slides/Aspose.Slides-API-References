---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Converts the character memory to a string representation.
type: docs
weight: 66
url: /system/memory/tostring/
---
## Memory::ToString() const method


Converts the character memory to a string representation.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, char16_t>::value, String>::type System::Memory<T>::ToString() const
```


### Return Value

A string representing the memory.

## Memory::ToString() const method


Converts the ordinary memory to a string representation.

```cpp
template<typename T1> std::enable_if<!std::is_same<T1, char16_t>::value, String>::type System::Memory<T>::ToString() const
```


### Return Value

A string representing the memory.

## See Also

* Class [String](../../string/)
* Class [Memory](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
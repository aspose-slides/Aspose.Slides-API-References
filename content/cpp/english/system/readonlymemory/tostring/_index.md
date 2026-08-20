---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Converts the character read-only memory to a string representation.
type: docs
weight: 27
url: /system/readonlymemory/tostring/
---
## ReadOnlyMemory::ToString() const method


Converts the character read-only memory to a string representation.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, char16_t>::value, String>::type System::ReadOnlyMemory<T>::ToString() const
```


### Return Value

A string representing the memory.

## ReadOnlyMemory::ToString() const method


Converts the ordinary read-only memory to a string representation.

```cpp
template<typename T1> std::enable_if<!std::is_same<T1, char16_t>::value, String>::type System::ReadOnlyMemory<T>::ToString() const
```


### Return Value

A string representing the memory.

## See Also

* Class [String](../../string/)
* Class [ReadOnlyMemory](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
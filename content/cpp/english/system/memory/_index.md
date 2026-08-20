---
title: Memory
second_title: Aspose.Slides for C++ API Reference
description: Represents a mutable memory segment backed by an array.
type: docs
weight: 1093
url: /system/memory/
---
## Memory class


Represents a mutable memory segment backed by an array.

```cpp
template<typename T>class Memory : public System::Details::MemoryCore<T>
```

## Methods

| Method | Description |
| --- | --- |
| void [CopyTo](./copyto/)(const [Memory](./)\&) | Copies the contents of this memory to the destination memory. |
| static [Memory](./) [get_Empty](./get_empty/)() | Gets an empty [Memory](./) instance. |
| [Span](../span/)\<T\> [get_Span](./get_span/)() const | Gets a span that represents the current memory. |
|  [operator ReadOnlyMemory< T >](./operator_readonlymemory_less_t__greater/)() const | Implicitly converts [Memory](./) to [ReadOnlyMemory](../readonlymemory/). |
| [Memory](./) [Slice](./slice/)(**int32_t**, **int32_t**) const | Creates a slice of the current memory. |
| static [Memory](./) [to_Memory](./to_memory/)(const [ArrayPtr](../arrayptr/)\<T\>\&) | Creates a [Memory](./) instance from the specified array. |
| std::enable_if\<std::is_same\<T1, char16_t\>::value, [String](../string/)\>::type [ToString](./tostring/)() const | Converts the character memory to a string representation. |
| std::enable_if<\!std::is_same\<T1, char16_t\>::value, [String](../string/)\>::type [ToString](./tostring/)() const | Converts the ordinary memory to a string representation. |
| **bool** [TryCopyTo](./trycopyto/)(const [Memory](./)\&) | Attempts to copy the contents of this memory to the destination memory. |
## Remarks


Exposes a span over the array region and supports slicing and copying. 
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
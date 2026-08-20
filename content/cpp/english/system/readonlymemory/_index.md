---
title: ReadOnlyMemory
second_title: Aspose.Slides for C++ API Reference
description: Represents a read-only memory segment backed by an array.
type: docs
weight: 1223
url: /system/readonlymemory/
---
## ReadOnlyMemory class


Represents a read-only memory segment backed by an array.

```cpp
template<typename T>class ReadOnlyMemory : public System::Details::MemoryCore<T>
```

## Methods

| Method | Description |
| --- | --- |
| static [ReadOnlyMemory](./) [get_Empty](./get_empty/)() | Gets an empty [ReadOnlyMemory](./) instance. |
| [ReadOnlySpan](../readonlyspan/)\<T\> [get_Span](./get_span/)() const | Gets a read-only span that represents the current memory. |
| [ReadOnlyMemory](./) [Slice](./slice/)(**int32_t**, **int32_t**) const | Creates a slice of the current readonly memory. |
| static [ReadOnlyMemory](./) [to_ReadOnlyMemory](./to_readonlymemory/)(const [ArrayPtr](../arrayptr/)\<T\>\&) | Creates a [ReadOnlyMemory](./) instance from the specified array. |
| std::enable_if\<std::is_same\<T1, char16_t\>::value, [String](../string/)\>::type [ToString](./tostring/)() const | Converts the character read-only memory to a string representation. |
| std::enable_if<\!std::is_same\<T1, char16_t\>::value, [String](../string/)\>::type [ToString](./tostring/)() const | Converts the ordinary read-only memory to a string representation. |
## Remarks


Exposes a read-only span over the array region and supports slicing. 
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
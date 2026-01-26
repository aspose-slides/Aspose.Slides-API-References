---
title: Span
second_title: Aspose.Slides for C++ API Reference
description: "Represents a contiguous region of arbitrary memory similar to C++20's std::span."
type: docs
weight: 1223
url: /system/span/
---
## Span class


Represents a contiguous region of arbitrary memory similar to C++20's std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span. This class provides a type-safe way to work with contiguous sequences of objects. It can be used to wrap arrays, stack arrays, or raw pointers while maintaining bounds checking. The [Span](./) doesn't own the memory it points to - it's just a view into existing memory. |
## Methods

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() const | Clears the contents of the span by setting all elements to default value. |
| void [Fill](./fill/)(const T\&) const | Fills the span with the specified value. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Converts an array to a [Span](./). |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
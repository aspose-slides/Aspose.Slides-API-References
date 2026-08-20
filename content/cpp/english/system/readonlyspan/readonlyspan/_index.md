---
title: ReadOnlySpan()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an empty read-only span.
type: docs
weight: 1
url: /system/readonlyspan/readonlyspan/
---
## ReadOnlySpan::ReadOnlySpan() constructor


Constructs an empty read-only span.

```cpp
System::ReadOnlySpan<T>::ReadOnlySpan()
```

## ReadOnlySpan::ReadOnlySpan(const Span\<T\>\&) constructor


Constructs a read-only span from a regular span.

```cpp
System::ReadOnlySpan<T>::ReadOnlySpan(const Span<T> &span)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../span/)\<T\>\& | The span to create a read-only view of. |

## ReadOnlySpan::ReadOnlySpan(const typename std::enable_if\<std::is_same\<T1, uint8_t\>::value, char\>::type(&)) constructor


Constructs a read-only span from a string literal.

```cpp
template<std::size_t,typename T1> System::ReadOnlySpan<T>::ReadOnlySpan(const typename std::enable_if<std::is_same<T1, uint8_t>::value, char>::type(&array)[N])
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | Literal size. |
| T1 | Serice SFINAE type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const typename std::enable_if\<std::is_same\<T1, **uint8_t**\>::value, char\>::type(&) | The span to create a read-only view of. |

## See Also

* Class [ReadOnlySpan](../)
* Class [Span](../../span/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: operator<()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 1925
url: /cpp/system/operator_less/
---
## System::operator<(std::nullptr_t, [DateTime](../datetime/)) function




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator<(std::nullptr_t, const [DateTimeOffset](../datetimeoffset/)\&) function




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator<(std::nullptr_t, const [Nullable](../nullable/)\<T\>\&) function


Always returns false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator<(const T1\&, const [Nullable](../nullable/)\<T2\>\&) function


Determines if the specified value is less than the value represented by the specified [Nullable](../nullable/) object by applying [operator<()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Return Value

True if the first comparand is less than the second comparand, otherwise - false

## See Also

* Struct [IsNullable](../isnullable/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator<(std::nullptr_t, [TimeSpan](../timespan/)) function




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)

---
title: operator<()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 1925
url: /cpp/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) function


Always returns false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) function


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

## System::operator<(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## See Also

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
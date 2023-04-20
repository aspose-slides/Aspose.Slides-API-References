---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts string to equivalent TimeSpan object.
type: docs
weight: 534
url: /cpp/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) method


Converts string to equivalent [TimeSpan](../) object.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |

### Return Value

Time interval that corresponds to string.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts string to equivalent [TimeSpan](../) object using the specified format provider.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |

### Return Value

Time interval that corresponds to string.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
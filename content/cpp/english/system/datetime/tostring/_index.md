---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Returns the string representation of the date and time value represented by the current object using the formatting conventions defined by the current culture.
type: docs
weight: 482
url: /system/datetime/tostring/
---
## DateTime::ToString() const method


Returns the string representation of the date and time value represented by the current object using the formatting conventions defined by the current culture.

```cpp
String System::DateTime::ToString() const
```


### Return Value

The string representation of the value represented by the current object

## DateTime::ToString(const String\&) const method


Returns a string representation of the date and time value represented by the current object using the specified format and formatting conventions defined by the current culture.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | A format string |

### Return Value

The string representation of the value represented by the current object formatted according to format defined by **format** and the current culture.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const method


Returns a string representation of the date and time value represented by the current object using the specified format information.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | An object representing the format information |

### Return Value

The string representation of the value represented by the current object formatted according to format information provided by **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const method




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const method




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method


Returns a string representation of the date and time value represented by the current object using the specified format information.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | A format string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | An object representing the format information |

### Return Value

The string representation of the value represented by the current object formatted according to format information provided by **provider** and format string **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const method




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const method




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
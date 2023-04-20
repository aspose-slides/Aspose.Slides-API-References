---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent 8-bit signed integer.
type: docs
weight: 14
url: /cpp/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 8-bit signed integer.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **int8_t**\& | The reference to a 8-bit signed integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 8-bit signed integer using the provided formatting information and number style.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **int8_t**\& | The reference to a 8-bit signed integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
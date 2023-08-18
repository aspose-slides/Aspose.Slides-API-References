---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer.
type: docs
weight: 14
url: /system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **uint16_t**\& | The reference to a 16-bit unsigned integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer using the provided formatting information and number style.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **uint16_t**\& | The reference to a 16-bit unsigned integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
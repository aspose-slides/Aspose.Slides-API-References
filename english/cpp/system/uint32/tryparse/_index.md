---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent 32-bit unsigned integer.
type: docs
weight: 14
url: /cpp/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 32-bit unsigned integer.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **uint32_t**\& | The reference to a 32-bit unsigned integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method


Converts the specified string containing the string representation of a number to the equivalent 32-bit unsigned integer using the provided formatting information and number style.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **uint32_t**\& | The reference to a 32-bit unsigned integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
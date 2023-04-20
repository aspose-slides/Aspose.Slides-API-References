---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer.
type: docs
weight: 1
url: /cpp/system/uint16/parse/
---
## UInt16::Parse(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |

### Return Value

The 16-bit unsigned integer equal to the number represented by the specified string.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer using the provided formatting information.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### Return Value

The 16-bit unsigned integer equal to the number represented by the specified string.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) method




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer using the provided formatting information and number style.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### Return Value

The 16-bit unsigned integer equal to the number represented by the specified string.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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
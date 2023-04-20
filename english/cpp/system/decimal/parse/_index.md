---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the string representation of a decimal number into an equivalent instance of Decimal class.
type: docs
weight: 469
url: /cpp/system/decimal/parse/
---
## Decimal::Parse(const String\&) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a number |

### Return Value

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string.

## Decimal::Parse(const String\&, Globalization::NumberStyles) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified style.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a decimal value to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [Decimal](../) object |

### Return Value

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified format provider.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a decimal value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider |

### Return Value

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified style and format provider.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | The string representation of a decimal value to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of the enumeration values that provides additional information about **s**, about style elements that may be present in **s**, or about the conversion from **s** to a [Decimal](../) object |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider |

### Return Value

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
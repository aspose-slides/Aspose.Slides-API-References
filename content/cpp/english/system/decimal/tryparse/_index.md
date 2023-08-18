---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent Decimal value.
type: docs
weight: 482
url: /system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../) value.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| result | [Decimal](../)\& | The reference to a [Decimal](../) variable where the result of the conversion is put |

### Return Value

True if the conversion succeeded, otherwise - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../) value using the provided formatting information and number style.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |
| result | [Decimal](../)\& | An output argument; contains the result of conversion |

### Return Value

True if the conversion succeeded, otherwise - false

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
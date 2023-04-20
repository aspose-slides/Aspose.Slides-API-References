---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value.
type: docs
weight: 14
url: /cpp/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **double**\& | The reference to a double-precision floating-point variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **double**\& | The reference to a double-precision floating-point variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
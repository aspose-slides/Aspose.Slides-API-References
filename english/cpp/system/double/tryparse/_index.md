---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value.
type: docs
weight: 14
url: /cpp/system/double/tryparse/
---
## Double::TryParse(const [String](../../string/)\&, **double**\&) method


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

## See Also

* Class [String](../../string/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Double::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, **double**\&) method


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

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Double::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, **double**\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Double::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[Globalization::NumberFormatInfo](../../../system.globalization/numberformatinfo/)\>\&, **double**\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Double::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)

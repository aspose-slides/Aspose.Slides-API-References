---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value.
type: docs
weight: 14
url: /cpp/system/single/tryparse/
---
## Single::TryParse(const [String](../../string/)\&, **float**\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **float**\& | The reference to a single-precision floating-point variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Single::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, **float**\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **float**\& | The reference to a single-precision floating-point variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Single::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, **float**\&) method




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Single::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[Globalization::NumberFormatInfo](../../../system.globalization/numberformatinfo/)\>\&, **float**\&) method




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Single::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) method




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)

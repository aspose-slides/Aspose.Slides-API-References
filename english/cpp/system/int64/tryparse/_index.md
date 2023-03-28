---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent 64-bit signed integer.
type: docs
weight: 14
url: /cpp/system/int64/tryparse/
---
## Int64::TryParse(const [String](../../string/)\&, **int64_t**\&) method


Converts the specified string containing the string representation of a number to the equivalent 64-bit signed integer.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **int64_t**\& | The reference to a 64-bit signed integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Int64::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\&, **int64_t**\&) method


Converts the specified string containing the string representation of a number to the equivalent 64-bit signed integer using the provided formatting information and number style.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **int64_t**\& | The reference to a 64-bit signed integer variable where the result of the conversion is put. |

### Return Value

True if the conversion succeeded, otherwise - false.

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Int64::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Int64::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), const [SharedPtr](../../sharedptr/)\<[Globalization::NumberFormatInfo](../../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Int64::TryParse(const [String](../../string/)\&, [Globalization::NumberStyles](../../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## See Also

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)

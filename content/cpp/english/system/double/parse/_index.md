---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value.
type: docs
weight: 1
url: /system/double/parse/
---
## Double::Parse(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value.

```cpp
static double System::Double::Parse(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |

### Return Value

The double-precision floating-point value equal to the number represented by the specified string.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### Return Value

The double-precision floating-point value equal to the number represented by the specified string.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) method




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### Return Value

The double-precision floating-point value equal to the number represented by the specified string.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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
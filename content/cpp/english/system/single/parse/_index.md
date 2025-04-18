---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value.
type: docs
weight: 1
url: /system/single/parse/
---
## Single::Parse(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value.

```cpp
static float System::Single::Parse(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |

### Return Value

The single-precision floating-point value equal to the number represented by the specified string.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### Return Value

The single-precision floating-point value equal to the number represented by the specified string.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) method




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |

### Return Value

The single-precision floating-point value equal to the number represented by the specified string.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
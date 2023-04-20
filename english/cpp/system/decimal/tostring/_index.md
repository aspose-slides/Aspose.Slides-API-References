---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Returns the string representation of the value represented by the object.
type: docs
weight: 352
url: /cpp/system/decimal/tostring/
---
## Decimal::ToString() const method


Returns the string representation of the value represented by the object.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const method


Converts current object to string using the culture-specific format information.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The [IFormatProvider](../../iformatprovider/) object providing the culture-specific format information. |

### Return Value

The string representation of the current object.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const method




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const method




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method


Converts current object to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../../iformatprovider/) object.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | The string format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The [IFormatProvider](../../iformatprovider/) object providing the culture-specific format information. |

### Return Value

The string representation of the current object.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const method




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const method




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
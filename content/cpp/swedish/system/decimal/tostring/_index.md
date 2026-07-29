---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar strängrepresentationen av värdet som representeras av objektet.
type: docs
weight: 352
url: /sv/system/decimal/tostring/
---
## Decimal::ToString() const metod


Returnerar strängrepresentationen av värdet som representeras av objektet.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const metod


Konverterar aktuellt objekt till sträng med den kultur-specifika formatinformationen.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kultur-specifik formatinformation. |

### Returvärde

Strängrepresentationen av det aktuella objektet.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metod




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metod




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const metod




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metod


Konverterar aktuellt objekt till dess strängrepresentation med det angivna strängformatet och den kultur-specifika formatinformationen som tillhandahålls av det angivna [IFormatProvider](../../iformatprovider/)-objektet.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | Strängformatet. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kultur-specifik formatinformation. |

### Returvärde

Strängrepresentationen av det aktuella objektet.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metod




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metod 




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const metod 




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Se även

* Typdefinition [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Decimal](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
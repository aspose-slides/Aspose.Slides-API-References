---
title: ToString()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací řetězcovou reprezentaci hodnoty představované objektem.
type: docs
weight: 352
url: /cs/system/decimal/tostring/
---
## Decimal::ToString() const metoda

Vrací řetězcovou reprezentaci hodnoty představované objektem.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const metoda

Převádí aktuální objekt na řetězec pomocí kulturně specifických formátovacích informací.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) objekt poskytující kulturně specifické formátovací informace. |

### Návratová hodnota

Řetězcová reprezentace aktuálního objektu.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const metoda




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metoda

Převádí aktuální objekt na jeho řetězcovou reprezentaci pomocí zadaného řetězcového formátu a kulturně specifických formátovacích informací poskytovaných zadaným [IFormatProvider](../../iformatprovider/) objektem.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Řetězcový formát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) objekt poskytující kulturně specifické formátovací informace. |

### Návratová hodnota

Řetězcová reprezentace aktuálního objektu.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const metoda




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Decimal](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)
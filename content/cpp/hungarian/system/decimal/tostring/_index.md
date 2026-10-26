---
title: ToString()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja az objektum által képviselt érték karakterlánc ábrázolását.
type: docs
weight: 352
url: /hu/system/decimal/tostring/
---
## Decimal::ToString() const metódus

Visszaadja az objektum által képviselt érték karakterlánc ábrázolását.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const metódus

Átalakítja a jelenlegi objektumot karakterlánccá a kultúra-specifikus formázási információk használatával.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A [IFormatProvider](../../iformatprovider/) objektum, amely a kultúra-specifikus formázási információkat biztosítja. |

### Visszatérési érték

A jelenlegi objektum karakterlánc ábrázolása.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metódus




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metódus




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const metódus




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metódus

Átalakítja a jelenlegi objektumot a saját karakterlánc ábrázolává a megadott karakterlánc formátum és a megadott [IFormatProvider](../../iformatprovider/) objektum által biztosított kultúra-specifikus formázási információk használatával.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | A karakterlánc formátuma. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A [IFormatProvider](../../iformatprovider/) objektum, amely a kultúra-specifikus formázási információkat biztosítja. |

### Visszatérési érték

A jelenlegi objektum karakterlánc ábrázolása.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metódus




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metódus




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const metódus




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Decimal](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)
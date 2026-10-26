---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeichenkettenrepräsentation des vom Objekt dargestellten Werts zurück.
type: docs
weight: 352
url: /de/system/decimal/tostring/
---
## Decimal::ToString() const method

Gibt die Zeichenkettenrepräsentation des vom Objekt dargestellten Werts zurück.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const method

Wandelt das aktuelle Objekt unter Verwendung der kulturspezifischen Formatinformationen in eine Zeichenkette um.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/) Objekt, das die kulturspezifischen Formatinformationen bereitstellt. |

### Rückgabewert

Die Zeichenkettenrepräsentation des aktuellen Objekts.

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

Wandelt das aktuelle Objekt unter Verwendung des angegebenen Zeichenkettenformats und der von dem angegebenen [IFormatProvider](../../iformatprovider/) Objekt bereitgestellten kulturspezifischen Formatinformationen in seine Zeichenkettenrepräsentation um.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../string/)\& | Das Zeichenkettenformat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/) Objekt, das die kulturspezifischen Formatinformationen bereitstellt. |

### Rückgabewert

Die Zeichenkettenrepräsentation des aktuellen Objekts.

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

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Decimal](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)
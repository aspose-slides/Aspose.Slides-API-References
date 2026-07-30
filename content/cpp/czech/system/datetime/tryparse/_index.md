---
title: TryParse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt DateTime.
type: docs
weight: 885
url: /cs/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../).

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, kterou převést. |
| result | [DateTime](../)\& | Výstupní argument, který v případě úspěšné konverze obsahuje výsledek převodu. |

### Návratová hodnota

True, pokud se konverze podaří, jinak - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../) pomocí zadaných kulturálně specifických formátovacích informací a stylu.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, kterou převést. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt [IFormatProvider](../../iformatprovider/), který poskytuje kulturálně specifické formátovací informace. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitová kombinace hodnot výčtu, která poskytuje dodatečné informace o **s**, o stylech, které mohou být v **s** přítomny, nebo o konverzi z **s** na objekt [DateTime](../). |
| result | [DateTime](../)\& | Výstupní argument, který v případě úspěšné konverze obsahuje výsledek převodu. |

### Návratová hodnota

True, pokud se konverze podaří, jinak - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Viz také

* Výčet [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [DateTime](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Prostor názvů [System](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: TryParseExact()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt DateTime pomocí zadaného formátu, informací o formátu specifických pro kulturu a stylu. Formát řetězcové reprezentace musí přesně odpovídat zadanému formátu.
type: docs
weight: 898
url: /cs/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../) pomocí zadaného formátu, informací o formátu specifických pro kulturu a stylu. Formát řetězcové reprezentace musí přesně odpovídat zadanému formátu.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, kterou je třeba převést. |
| format | const [String](../../string/)\& | Formát řetězce. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt [IFormatProvider](../../iformatprovider/), který poskytuje informace o formátu specifické pro kulturu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitová kombinace hodnot výčtu, která poskytuje dodatečné informace o **s**, o stylech, které mohou být v **s** přítomny, nebo o převodu z **s** na objekt [DateTime](../). |
| result | [DateTime](../)\& | Výstupní argument, který v případě úspěšného převodu obsahuje výsledek převodu. |

### Návratová hodnota

True pokud převod uspěje, jinak - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../) pomocí zadaných formátů, informací o formátu specifických pro kulturu a stylu. Formát řetězcové reprezentace musí přesně odpovídat jednomu nebo více ze zadaných formátů.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, kterou je třeba převést. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Pole řetězcových formátů. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt [IFormatProvider](../../iformatprovider/), který poskytuje informace o formátu specifické pro kulturu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitová kombinace hodnot výčtu, která poskytuje dodatečné informace o **s**, o stylech, které mohou být v **s** přítomny, nebo o převodu z **s** na objekt [DateTime](../). |
| result | [DateTime](../)\& | Výstupní argument, který v případě úspěšného převodu obsahuje výsledek převodu. |

### Návratová hodnota

True pokud převod uspěje, jinak - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metoda

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Viz také

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [DateTime](../)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)
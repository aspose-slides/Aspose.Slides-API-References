---
title: ParseExact()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt DateTime pomocí zadaného formátu a informací o formátování specifických pro kulturu. Formát řetězcové reprezentace musí přesně odpovídat zadanému formátu. Vyvolá výjimku, pokud převod selže.
type: docs
weight: 872
url: /cs/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../) pomocí zadaného formátu a informací o formátování specifických pro kulturu. Formát řetězcové reprezentace musí přesně odpovídat zadanému formátu. Vyvolá výjimku, pokud převod selže.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, která se má převést. |
| format | const [String](../../string/)\& | Formát řetězce. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt [IFormatProvider](../../iformatprovider/), který poskytuje informace o formátování specifické pro kulturu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitový součet hodnot enumerace, který poskytuje dodatečné informace o **s**, o prvcích stylu, které mohou být v **s** přítomny, nebo o převodu z **s** na objekt [DateTime](../). |

### Návratová hodnota

Nová instance třídy [DateTime](../), která představuje hodnotu data a času ekvivalentní té, kterou představuje zadaný řetězec.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../) pomocí zadaných formátů, informací o formátování specifických pro kulturu a stylu. Formát řetězcové reprezentace musí přesně odpovídat jednomu nebo více zadaným formátům. Vyvolá výjimku, pokud převod selže.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, která se má převést. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Pole řetězcových formátů. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt [IFormatProvider](../../iformatprovider/), který poskytuje informace o formátování specifické pro kulturu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitový součet hodnot enumerace, který poskytuje dodatečné informace o **s**, o prvcích stylu, které mohou být v **s** přítomny, nebo o převodu z **s** na objekt [DateTime](../). |

### Návratová hodnota

Nová instance třídy [DateTime](../), která představuje hodnotu data a času ekvivalentní té, kterou představuje zadaný řetězec.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Viz také

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
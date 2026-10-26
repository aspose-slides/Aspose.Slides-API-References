---
title: ParseExact()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het overeenkomstige DateTime object met behulp van het opgegeven formaat en cultuurspecifieke formaat informatie. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met het opgegeven formaat. Werpt een uitzondering als de conversie mislukt.
type: docs
weight: 872
url: /nl/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) methode


Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het overeenkomstige [DateTime](../) object met behulp van het opgegeven formaat en cultuurspecifieke formaat informatie. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met het opgegeven formaat. Werpt een uitzondering als de conversie mislukt.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een datum- en tijdwaarde die moet worden geconverteerd. |
| format | const [String](../../string/)\& | Het tekenreeksformaat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/) object dat cultuurspecifieke formaat informatie biedt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Een bitwise combinatie van de enumeratiewaarden die extra informatie geeft over **s**, over stijl elementen die aanwezig kunnen zijn in **s**, of over de conversie van **s** naar een [DateTime](../) object. |

### Retourwaarde

Een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die gelijk is aan die welke wordt weergegeven door de opgegeven tekenreeks.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) methode


Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het overeenkomstige [DateTime](../) object met behulp van de opgegeven formaten, cultuurspecifieke formaat informatie en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met een of meer van de opgegeven formaten. Werpt een uitzondering als de conversie mislukt.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een datum- en tijdwaarde die moet worden geconverteerd. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | De array van tekenreeksformaten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/) object dat cultuurspecifieke formaat informatie biedt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Een bitwise combinatie van de enumeratiewaarden die extra informatie geeft over **s**, over stijl elementen die aanwezig kunnen zijn in **s**, of over de conversie van **s** naar een [DateTime](../) object. |

### Retourwaarde

Een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die gelijk is aan die welke wordt weergegeven door de opgegeven tekenreeks.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [DateTime](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)
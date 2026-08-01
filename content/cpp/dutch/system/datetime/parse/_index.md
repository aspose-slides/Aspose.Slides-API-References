---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente DateTime object.
type: docs
weight: 859
url: /nl/system/datetime/parse/
---
## DateTime::Parse(const String\&) methode


Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](../) object.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een datum- en tijdwaarde die moet worden geconverteerd. |

### Retourwaarde

Een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die gelijk is aan diegene die door de opgegeven tekenreeks wordt weergegeven.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) methode


Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](../) object met behulp van cultuur-specifieke opmaakinformatie.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een datum- en tijdwaarde die moet worden geconverteerd. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/) object dat cultuur-specifieke opmaakinformatie levert. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Een bitgewijze combinatie van de enumeratiewaarden die extra informatie biedt over **s**, over stijlelementen die mogelijk in **s** aanwezig zijn, of over de conversie van **s** naar een [DateTime](../) object. |

### Retourwaarde

Een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die gelijk is aan diegene die door de opgegeven tekenreeks wordt weergegeven.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) methode




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [DateTime](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
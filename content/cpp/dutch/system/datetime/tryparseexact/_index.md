---
title: TryParseExact()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente DateTime-object met behulp van het gespecificeerde formaat, cultuur-specifieke opmaakinformatie en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met het opgegeven formaat.
type: docs
weight: 898
url: /nl/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) methode


Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](../)-object met behulp van het gespecificeerde formaat, cultuur-specifieke opmaakinformatie en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met het opgegeven formaat.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een datum- en tijdwaarde die moet worden geconverteerd. |
| format | const [String](../../string/)\& | Het tekenreeksformaat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/)-object dat cultuur-specifieke opmaakinformatie levert. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Een bitgewijze combinatie van de enumeratiewaarden die extra informatie geeft over **s**, over stijlelementen die in **s** aanwezig kunnen zijn, of over de conversie van **s** naar een [DateTime](../)-object. |
| result | [DateTime](../)\& | Het uitvoerargument dat, als de conversie slaagt, het resultaat van de conversie bevat. |

### Retourwaarde

True if conversion succeeds, otherwise - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) methode


Converteert de opgegeven tekenreeksrepresentatie van een datum- en tijdwaarde naar het equivalente [DateTime](../)-object met behulp van de opgegeven formaten, cultuur-specifieke opmaakinformatie en stijl. Het formaat van de tekenreeksrepresentatie moet exact overeenkomen met een of meer van de opgegeven formaten.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een datum- en tijdwaarde die moet worden geconverteerd. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | De array van tekenreeksformaten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/)-object dat cultuur-specifieke opmaakinformatie levert. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Een bitgewijze combinatie van de enumeratiewaarden die extra informatie geeft over **s**, over stijlelementen die in **s** aanwezig kunnen zijn, of over de conversie van **s** naar een [DateTime](../)-object. |
| result | [DateTime](../)\& | Het uitvoerargument dat, als de conversie slaagt, het resultaat van de conversie bevat. |

### Retourwaarde

True if conversion succeeds, otherwise - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Zie ook

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [DateTime](../)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
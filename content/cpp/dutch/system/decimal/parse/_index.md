---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de tekenreeksrepresentatie van een decimaal getal naar een gelijkwaardig exemplaar van de Decimal-klasse.
type: docs
weight: 469
url: /nl/system/decimal/parse/
---
## Decimal::Parse(const String\&) methode

Converteert de tekenreeksrepresentatie van een decimaal getal naar een gelijkwaardig exemplaar van de klasse [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een getal |

### Retourwaarde

Een nieuw exemplaar van de klasse [Decimal](../) dat een waarde vertegenwoordigt die gelijk is aan die welke door de opgegeven tekenreeks wordt weergegeven.

## Decimal::Parse(const String\&, Globalization::NumberStyles) methode

Converteert de tekenreeksrepresentatie van een decimaal getal naar een gelijkwaardig exemplaar van de klasse [Decimal](../) met behulp van de opgegeven stijl.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een decimale waarde die moet worden geconverteerd |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van de enumeratiewaarden die aanvullende informatie verstrekt over **s**, over stijlelementen die in **s** aanwezig kunnen zijn, of over de conversie van **s** naar een [Decimal](../)-object |

### Retourwaarde

Een nieuw exemplaar van de klasse [Decimal](../) dat een waarde vertegenwoordigt die gelijk is aan die welke door de opgegeven tekenreeks wordt weergegeven.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de tekenreeksrepresentatie van een decimaal getal naar een gelijkwaardig exemplaar van de klasse [Decimal](../) met behulp van de opgegeven opmaakprovider.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een decimale waarde die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Opmaakprovider |

### Retourwaarde

Een nieuw exemplaar van de klasse [Decimal](../) dat een waarde vertegenwoordigt die gelijk is aan die welke door de opgegeven tekenreeks wordt weergegeven.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de tekenreeksrepresentatie van een decimaal getal naar een gelijkwaardig exemplaar van de klasse [Decimal](../) met behulp van de opgegeven stijl en opmaakprovider.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../string/)\& | De tekenreeksrepresentatie van een decimale waarde die moet worden geconverteerd |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van de enumeratiewaarden die aanvullende informatie verstrekt over **s**, over stijlelementen die in **s** aanwezig kunnen zijn, of over de conversie van **s** naar een [Decimal](../)-object |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Opmaakprovider |

### Retourwaarde

Een nieuw exemplaar van de klasse [Decimal](../) dat een waarde vertegenwoordigt die gelijk is aan die welke door de opgegeven tekenreeks wordt weergegeven.

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)
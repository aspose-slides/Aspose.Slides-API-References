---
title: GetDateTimeFormats()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, geformatteerd met een van de standaard datum- en tijdnotaties.
type: docs
weight: 547
url: /nl/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const methode

Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, geformatteerd met één van de standaard datum- en tijdnotaties.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const methode

Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, geformatteerd met de opgegeven standaard datum- en tijdnotatie.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | char_t | Standaard datum- en tijdnotatie. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const methode

Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, geformatteerd met één van de standaard datum- en tijdnotaties en de opgegeven formatprovider.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const methode

Retourneert een array van strings waarbij elk element de tekenreeksrepresentatie van het huidige object is, geformatteerd met de opgegeven standaard datum- en tijdnotatie en de opgegeven formatprovider.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | char_t | Standaard datum- en tijdnotatie. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider. |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [DateTime](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)
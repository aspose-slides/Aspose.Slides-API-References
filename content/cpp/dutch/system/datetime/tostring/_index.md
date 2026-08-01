---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekenreeksrepresentatie van de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd, met behulp van de opmaakconventies die door de huidige cultuur zijn gedefinieerd.
type: docs
weight: 482
url: /nl/system/datetime/tostring/
---
## DateTime::ToString() const methode


Retourneert de tekenreeksrepresentatie van de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd, met behulp van de opmaakconventies die door de huidige cultuur zijn gedefinieerd.

```cpp
String System::DateTime::ToString() const
```


### Retourwaarde

De tekenreeksrepresentatie van de waarde die door het huidige object wordt vertegenwoordigd

## DateTime::ToString(const String\&) const methode


Retourneert een tekenreeksrepresentatie van de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd, met behulp van het opgegeven formaat en de opmaakconventies die door de huidige cultuur zijn gedefinieerd.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../string/)\& | Een opmaakreeks |

### Retourwaarde

De tekenreeksrepresentatie van de waarde die door het huidige object wordt vertegenwoordigd, opgemaakt volgens het door **format** gedefinieerde formaat en de huidige cultuur.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const methode


Retourneert een tekenreeksrepresentatie van de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd, met behulp van de opgegeven opmaakinformatie.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een object dat de opmaakinformatie vertegenwoordigt |

### Retourwaarde

De tekenreeksrepresentatie van de waarde die door het huidige object wordt vertegenwoordigd, opgemaakt volgens de opmaakinformatie geleverd door **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const methode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const methode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const methode




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const methode


Retourneert een tekenreeksrepresentatie van de datum- en tijdwaarde die door het huidige object wordt vertegenwoordigd, met behulp van de opgegeven opmaakinformatie.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../string/)\& | Een opmaakreeks |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een object dat de opmaakinformatie vertegenwoordigt |

### Retourwaarde

De tekenreeksrepresentatie van de waarde die door het huidige object wordt vertegenwoordigd, opgemaakt volgens de opmaakinformatie geleverd door **provider** en de opmaakreeks **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const methode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const methode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const methode




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [DateTime](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de GUID die door het huidige object wordt vertegenwoordigd naar zijn tekenreeksrepresentatie.
type: docs
weight: 79
url: /nl/system/guid/tostring/
---
## Guid::ToString() const methode


Converteert de GUID die door het huidige object wordt vertegenwoordigd naar zijn tekenreeksrepresentatie.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const methode


Converteert de GUID die door het huidige object wordt vertegenwoordigd naar zijn tekenreeksrepresentatie met behulp van het gespecificeerde tekenreeksformaat.

```cpp
String System::Guid::ToString(const String &format) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../string/)\& | Het te gebruiken formaat |

### Retourwaarde

De tekenreeksrepresentatie van de GUID-waarde die door het huidige object wordt vertegenwoordigd

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const methode


Converteert de GUID die door het huidige object wordt vertegenwoordigd naar zijn tekenreeksrepresentatie met behulp van het gespecificeerde tekenreeksformaat en cultuur.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../string/)\& | Het te gebruiken formaat |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Te gebruiken cultuur |

### Retourwaarde

De tekenreeksrepresentatie van de GUID-waarde die door het huidige object wordt vertegenwoordigd

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Guid](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
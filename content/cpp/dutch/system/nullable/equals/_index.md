---
title: Equals()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object gelijk is aan de waarde die wordt weergegeven door het opgegeven Nullable-object.
type: docs
weight: 131
url: /nl/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const methode

Bepaalt of de waarde die door het huidige object wordt weergegeven gelijk is aan de waarde die door het opgegeven [Nullable](../) object wordt weergegeven.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het onderliggende type van het [Nullable](../) object waarmee vergeleken wordt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | Een constante referentie naar het [Nullable](../) object waarmee vergeleken wordt |

### Retourwaarde

Waar als de waarde die wordt weergegeven door het huidige object gelijk is aan de waarde die wordt weergegeven door het opgegeven [Nullable](../) object, anders - onwaar

## Zie ook

* Klasse [Nullable](../)
* Structuur [IsNullable](../../isnullable/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
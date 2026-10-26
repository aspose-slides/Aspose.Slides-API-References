---
title: operator<()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert altijd false.
type: docs
weight: 170
url: /nl/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const methode


Retourneert altijd false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const methode


Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object kleiner is dan de opgegeven waarde door [operator<()](./) op deze waarden toe te passen.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de waarde om mee te vergelijken |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | Een constante referentie naar de waarde om mee te vergelijken |

### Retourwaarde

True als de waarde die wordt vertegenwoordigd door het huidige object kleiner is dan de opgegeven waarde, anders - false

## Nullable::operator<(const Nullable\<T1\>\&) const methode


Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object kleiner is dan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](../) object door [operator<()](./) op deze waarden toe te passen.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het onderliggende type van het [Nullable](../) object om mee te vergelijken |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Een constante referentie naar het [Nullable](../) object om mee te vergelijken |

### Retourwaarde

True als de waarde die wordt vertegenwoordigd door het huidige object kleiner is dan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](../) object, anders - false

## Zie ook

* Klasse [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
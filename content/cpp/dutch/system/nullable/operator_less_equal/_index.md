---
title: operator<=()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft altijd false terug.
type: docs
weight: 196
url: /nl/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const method


Geeft altijd false terug.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const method


Bepaalt of de waarde die door het huidige object wordt vertegenwoordigd kleiner of gelijk is aan de opgegeven waarde door [operator<=()](./) op deze waarden toe te passen.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de te vergelijken waarde |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | Een constante referentie naar de te vergelijken waarde |

### Retourwaarde

True als de waarde die door het huidige object wordt vertegenwoordigd kleiner of gelijk is aan de opgegeven waarde, anders - false

## Nullable::operator<=(const Nullable\<T1\>\&) const method


Bepaalt of de waarde die door het huidige object wordt vertegenwoordigd kleiner of gelijk is aan de waarde die door het opgegeven [Nullable](../)-object wordt vertegenwoordigd door [operator<=()](./) op deze waarden toe te passen.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het onderliggende type van het [Nullable](../)-object om mee te vergelijken |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Een constante referentie naar het [Nullable](../)-object om mee te vergelijken |

### Retourwaarde

True als de waarde die door het huidige object wordt vertegenwoordigd kleiner of gelijk is aan de waarde die door het opgegeven [Nullable](../)-object wordt vertegenwoordigd, anders - false

## Zie ook

* Klasse [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
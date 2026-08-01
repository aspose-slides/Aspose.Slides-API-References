---
title: operator==()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de waarde die door het huidige object wordt gerepresenteerd null is.
type: docs
weight: 118
url: /nl/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const method


Bepaalt of de waarde die door het huidige object wordt gerepresenteerd null is.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Retourwaarde

True als de waarde die door het huidige object wordt gerepresenteerd null is, anders - false

## Nullable::operator==(const T1\&) const method


Bepaalt of de waarde die door het huidige object wordt gerepresenteerd gelijk is aan de opgegeven waarde.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de waarde waarmee vergeleken wordt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | Een constante referentie naar de waarde waarmee vergeleken wordt |

### Retourwaarde

True als de waarde die door het huidige object wordt gerepresenteerd gelijk is aan de opgegeven waarde, anders - false

## Nullable::operator==(const Nullable\<T1\>\&) const method


Bepaalt of de waarde die door het huidige object wordt gerepresenteerd gelijk is aan de waarde die wordt gerepresenteerd door het opgegeven [Nullable](../) object.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het onderliggende type van het [Nullable](../) object waarmee vergeleken wordt |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Een constante referentie naar het [Nullable](../) object waarmee vergeleken wordt |

### Retourwaarde

True als de waarde die door het huidige object wordt gerepresenteerd gelijk is aan de waarde die wordt gerepresenteerd door het opgegeven [Nullable](../) object, anders - false

## Zie ook

* Klasse [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
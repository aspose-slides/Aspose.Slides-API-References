---
title: operator-=()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een instantie van de Nullable-klasse die een null-waarde vertegenwoordigt.
type: docs
weight: 248
url: /nl/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) methode


Retourneert een instantie van de [Nullable](../) klasse die een null-waarde vertegenwoordigt.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) methode


Past [operator-=()](./) toe op de waarde die wordt weergegeven door het huidige object met de opgegeven waarde als rechterargument.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de waarde die wordt gebruikt als rechterwaarde van [operator-=()](./) |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | Een constante referentie naar de waarde die wordt gebruikt als rechterwaarde van de [operator-=()](./) toegepast op de waarde die wordt weergegeven door het huidige object. |

### Retourwaarde

Een referentie naar zichzelf

## Nullable::operator-=(const Nullable\<T1\>\&) methode


Past [operator-=()](./) toe op de waarde die wordt weergegeven door het huidige object met de waarde die wordt weergegeven door het opgegeven [Nullable](../)-object als rechterargument.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het onderliggende type van een [Nullable](../)-object waarvan de waarde wordt gebruikt als rechterargument van [operator-=()](./) |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Een constante referentie naar het [Nullable](../)-object waarvan de waarde wordt gebruikt als rechterargument van de [operator-=()](./) toegepast op de waarde die wordt weergegeven door het huidige object. |

### Retourwaarde

Een referentie naar zichzelf

## Zie ook

* Klasse [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
---
title: operator+=()
second_title: Aspose.Slides voor C++ API-referentie
description: Reset het huidige object zodat het een null-waarde vertegenwoordigt.
type: docs
weight: 235
url: /nl/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) method

Reset het huidige object zodat het een null-waarde vertegenwoordigt.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Retourwaarde

Een kopie van het object zelf

## Nullable::operator+=(const T1\&) method

Past [operator+=()](./) toe op de waarde die wordt vertegenwoordigd door het huidige object met de opgegeven waarde als rechterargument.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de waarde die wordt gebruikt als rechterwaarde van [operator+=()](./) |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | Een constante referentie naar de waarde die wordt gebruikt als rechterwaarde van de [operator+=()](./) die wordt toegepast op de waarde die wordt vertegenwoordigd door het huidige object. |

### Retourwaarde

Een referentie naar het object zelf

## Nullable::operator+=(const Nullable\<T1\>\&) method

Past [operator+=()](./) toe op de waarde die wordt vertegenwoordigd door het huidige object met de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](../)-object als rechterargument.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het onderliggende type van een [Nullable](../)-object waarvan de waarde wordt gebruikt als rechterargument van [operator+=()](./) |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Een constante referentie naar het [Nullable](../)-object waarvan de waarde wordt gebruikt als rechterargument van de [operator+=()](./) die wordt toegepast op de waarde die wordt vertegenwoordigd door het huidige object. |

### Retourwaarde

Een referentie naar het object zelf

## Zie ook

* Klasse [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)
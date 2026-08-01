---
title: Nullable()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een instantie die een null-waarde vertegenwoordigt.
type: docs
weight: 1
url: /nl/system/nullable/nullable/
---
## Nullable::Nullable() constructor

Construeert een instantie die een null-waarde vertegenwoordigt.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) constructor

Construeert een instantie die null vertegenwoordigt.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) constructor

Construeert een instantie van de [Nullable](../) klasse die de opgegeven waarde vertegenwoordigt, geconverteerd (indien nodig) naar de waarde van het onderliggende type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de opgegeven waarde |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T1\& | Een constante referentie naar de waarde die wordt weergegeven door het nieuw geconstrueerde [Nullable](../) object |

## Nullable::Nullable(const Nullable\<T1\>\&) constructor

Construeert een instantie die een waarde vertegenwoordigt die wordt weergegeven door het opgegeven [Nullable](../) object. Het opgegeven nullable-object kan een waarde van een ander type vertegenwoordigen dan het onderliggende type van de geconstrueerde instantie; in dat geval wordt de vertegenwoordigde waarde geconverteerd naar een waarde van type T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Het type van de waarde die wordt weergegeven door het opgegeven [Nullable](../) object |

## Zie ook

* Klasse [Nullable](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
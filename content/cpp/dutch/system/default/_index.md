---
title: Default()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de referentie naar de enige standaard-geconstrueerde instantie van het exceptietype.
type: docs
weight: 2224
url: /nl/system/default/
---
## System::Default() functie

Retourneert de referentie naar de enige standaard-geconstrueerde instantie van het exceptietype.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type waarvan de instantie wordt geretourneerd |

## System::Default() functie

Retourneert de referentie naar de enige standaard-geconstrueerde instantie van het niet-exceptietype.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type waarvan de instantie wordt geretourneerd |

## Zie ook

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
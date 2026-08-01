---
title: operator|=()
second_title: Aspose.Slides voor C++ API-referentie
description: Past operator|=() toe op de waarde die door het huidige object wordt vertegenwoordigd met de opgegeven waarde als rechter argument.
type: docs
weight: 261
url: /nl/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) methode


Past [operator|=()](./) toe op de waarde die door het huidige object wordt vertegenwoordigd met de opgegeven waarde als rechter argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | De sjabloonparameter om SFINAE te laten werken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | **bool** | Een booleaanse waarde die wordt gebruikt als rechterkantwaarde van de [operator|=()](./) toegepast op de waarde die door het huidige object wordt vertegenwoordigd. |

### Retourwaarde

Een verwijzing naar zichzelf.

## Zie ook

* Klasse [Nullable](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
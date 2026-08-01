---
title: operator&=()
second_title: Aspose.Slides voor C++ API-referentie
description: Past operator&=() toe op de waarde die door het huidige object wordt gerepresenteerd, met de opgegeven waarde als rechterargument.
type: docs
weight: 274
url: /nl/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) methode

Past [operator&=()](./) toe op de waarde die door het huidige object wordt gerepresenteerd, met de opgegeven waarde als rechterargument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | The template parameter to make SFINAE work. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | **bool** | Een booleaanse waarde die wordt gebruikt als rechterwaarde van de [operator&=()](./) toegepast op de waarde die door het huidige object wordt gerepresenteerd. |

### Retourwaarde

Een referentie naar zichzelf.

## Zie ook

* Klasse [Nullable](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
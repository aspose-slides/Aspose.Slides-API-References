---
title: operator|=()
second_title: Aspose.Slides für C++ API-Referenz
description: Wendet operator|=() auf den durch das aktuelle Objekt dargestellten Wert an, wobei der angegebene Wert als Rechtsargument verwendet wird.
type: docs
weight: 261
url: /de/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) Methode

Wendet [operator|=()](./) auf den durch das aktuelle Objekt dargestellten Wert an, wobei der angegebene Wert als Rechtsargument verwendet wird.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Template-Parameter, damit SFINAE funktioniert. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | **bool** | Ein boolescher Wert, der als Rechtswert des [operator|=()](./) verwendet wird, das auf den durch das aktuelle Objekt dargestellten Wert angewendet wird. |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt.

## Siehe auch

* Klasse [Nullable](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
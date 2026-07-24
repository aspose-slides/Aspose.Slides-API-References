---
title: operator&=()
second_title: Aspose.Slides für C++ API-Referenz
description: Wendet operator&=() auf den vom aktuellen Objekt repräsentierten Wert an und verwendet den angegebenen Wert als Rechtsargument.
type: docs
weight: 274
url: /de/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) Methode

Wendet [operator&=()](./) auf den vom aktuellen Objekt repräsentierten Wert an und verwendet den angegebenen Wert als Rechtswert-Argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Template-Parameter, um SFINAE zu aktivieren. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | **bool** | Ein boolescher Wert, der als Rechtswert von [operator&=()](./) verwendet wird, das auf den vom aktuellen Objekt repräsentierten Wert angewendet wird. |

### Rückgabewert

Eine Referenz auf das Objekt selbst.

## Siehe Auch

* Klasse [Nullable](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
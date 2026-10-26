---
title: NullableBoolHelper()
second_title: Aspose.Slides für C++ API-Referenz
description: Hilfsfunktion, um zu prüfen, ob sowohl this als auch other nicht null sind und in diesem Fall ein Lambda aufzurufen. Wird in implementation.s verwendet.
type: docs
weight: 105
url: /de/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const Methode

Hilfsfunktion, um zu prüfen, ob sowohl **this** als auch **other** nicht null sind und in diesem Fall ein Lambda aufzurufen. Verwendet in implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Other nullable type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const T1\& | Anderer nullable Wert, mit dem verglichen wird. |
| f | const std::function\<**bool**()>\& | Lambda, das aufgerufen wird, wenn sowohl **this** als auch **other** nicht null sind. |
| default_if_both_are_null | **bool** | Rückgabewert, wenn beide Werte null sind. |

### Rückgabewert

false, wenn entweder **this** oder **other** null ist; **default_if_both_are_null**, wenn beide null sind; Ergebnis des Aufrufs von **f**, wenn beide nicht null sind.

## Siehe auch

* Klasse [Nullable](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
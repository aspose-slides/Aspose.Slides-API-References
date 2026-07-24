---
title: operator!=()
second_title: Aspose.Slides für C++ API-Referenz
description: Ungleichheitsoperator.
type: docs
weight: 313
url: /de/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const Methode


Ungleichheitsoperator.

```cpp
bool System::String::operator!=(const String &str) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) zum Vergleich mit dem aktuellen. |

### Rückgabewert

false, wenn beide Zeichenketten null sind oder beide nicht null und übereinstimmen, ansonsten true.

## String::operator!=(std::nullptr_t) const Methode


Prüft, ob die Zeichenkette nicht null ist. Verwendet dieselbe Logik wie der Aufruf von [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### Rückgabewert

false, wenn die Zeichenkette null ist, ansonsten true.

## Siehe auch

* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
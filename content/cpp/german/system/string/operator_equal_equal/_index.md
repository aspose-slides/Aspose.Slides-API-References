---
title: operator==()
second_title: Aspose.Slides für C++ API-Referenz
description: Operator zum Vergleich von Gleichheit.
type: docs
weight: 300
url: /de/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const Methode

Vergleichsoperator für Gleichheit.

```cpp
bool System::String::operator==(const String &str) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) zum Vergleich mit dem aktuellen. |

### Rückgabewert

true, wenn beide Zeichenketten null sind oder beide nicht null und übereinstimmen, sonst false.

## String::operator==(std::nullptr_t) const Methode

Prüft, ob die Zeichenkette null ist. Verwendet dieselbe Logik wie der Aufruf von [IsNull()](../isnull/).

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Rückgabewert

true, wenn die Zeichenkette null ist, sonst false.

## Siehe Auch

* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
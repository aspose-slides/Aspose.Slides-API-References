---
title: Round()
second_title: Aspose.Slides für C++ API Referenz
description: Rundet den angegebenen Wert auf die nächste Ganzzahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleichermaßen nahe an zwei nächsten Zahlen liegt.
type: docs
weight: 404
url: /de/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) method

Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleichermaßen nahe an zwei nächsten Zahlen liegt.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../)\& | Der zu rundende Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichermaßen nahe an zwei nächsten Zahlen liegt. |

### Rückgabewert

**d** gerundet auf den nächsten Ganzzahlwert

## Decimal::Round(const Decimal\&, int, MidpointRounding) method

Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleichermaßen nahe an zwei nächsten Zahlen liegt.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../)\& | Der zu rundende Wert |
| digits | int | Die Anzahl der Nachkommastellen im gerundeten Wert |
| mode | [MidpointRounding](../../midpointrounding/) | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleichermaßen nahe an zwei nächsten Zahlen liegt. |

### Rückgabewert

Die Zahl mit der angegebenen Anzahl von Stellen, die **value** am nächsten liegt

## Siehe auch

* Enum [MidpointRounding](../../midpointrounding/)
* Klasse [Decimal](../)
* Namespace [System](../../)
* Bibliothek [Aspose.Slides](../../../)
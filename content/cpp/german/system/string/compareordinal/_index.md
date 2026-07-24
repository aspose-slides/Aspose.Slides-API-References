---
title: CompareOrdinal()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Zeichenketten im ordinalen Modus (weniger-gleich-größer).
type: docs
weight: 833
url: /de/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) Methode

Vergleicht zwei Zeichenketten im ordinalen Modus (weniger-gleich-großer).

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |

### Rückgabewert

Negativer Wert, wenn das erste Teilstring kleiner ist als das zweite, null wenn sie übereinstimmen, sonst ein positiver Wert.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) Methode

Vergleicht zwei Zeichenketten im ordinalen Modus (weniger-gleich-großer).

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| indexA | int | Anfang des Teilstrings der ersten Zeichenkette. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| indexB | int | Anfang des Teilstrings der zweiten Zeichenkette. |
| length | int | Anzahl der zu vergleichenden Zeichen. |

### Rückgabewert

Negativer Wert, wenn das erste Teilstring kleiner ist als das zweite, null wenn sie übereinstimmen, sonst ein positiver Wert.

## Siehe auch

* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
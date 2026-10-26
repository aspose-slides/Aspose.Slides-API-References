---
title: SpecifyKind()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues DateTime-Objekt, das die gleiche Anzahl von Ticks wie das angegebene DateTime-Objekt darstellt und lokale Zeit, UTC-Zeit oder wederes repräsentiert, wie durch das Argument kind angegeben.
type: docs
weight: 833
url: /de/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) Methode

Erstellt ein neues [DateTime](../) Objekt, das die gleiche Anzahl von Ticks wie das angegebene [DateTime](../) Objekt darstellt und lokale Zeit, UTC-Zeit oder wederes repräsentiert, wie durch das Argument **kind** angegeben.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DateTime](../) | Das [DateTime](../) Objekt, aus dem die Anzahl der Ticks kopiert wird |
| kind | [DateTimeKind](../../datetimekind/) | Gibt an, ob das neue Objekt lokale Zeit, UTC-Zeit oder wederes darstellen soll. |

### Rückgabewert

Ein neues [DateTime](../) Objekt, das die gleiche Anzahl von Ticks wie **value** und den von **kind** angegebenen DateTimeKind-Wert darstellt.

## Siehe auch

* Aufzählung [DateTimeKind](../../datetimekind/)
* Klasse [DateTime](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
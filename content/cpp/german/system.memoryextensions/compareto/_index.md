---
title: CompareTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Zeichenspannen mit den angegebenen Regeln für den String-Vergleich.
type: docs
weight: 404
url: /de/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) Funktion

Vergleicht zwei Zeichenspannen mit den angegebenen Regeln für den String-Vergleich.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Die erste Zeichenspanne |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Die zweite Zeichenspanne |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Der Typ des durchzuführenden String-Vergleichs |

### Rückgabewert

Negativer Wert, wenn span < other, null bei Gleichheit, positiver Wert, wenn span > other

## Siehe auch

* Aufzählung [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)
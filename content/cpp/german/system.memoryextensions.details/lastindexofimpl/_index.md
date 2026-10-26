---
title: LastIndexOfImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet den letzten Index eines Wertes in einem Span.
type: docs
weight: 14
url: /de/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function

Findet den letzten Index eines Wertes in einem Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) zum Suchen |
| length | **int32_t** | Länge, in der gesucht wird |
| value | const T\& | Zu findender Wert |

### Rückgabewert

Letzter Index des Wertes oder -1, wenn nicht gefunden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)
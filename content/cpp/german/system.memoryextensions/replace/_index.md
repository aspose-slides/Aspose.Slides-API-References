---
title: Replace()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt alle Vorkommen eines Wertes durch einen neuen Wert in einem Span.
type: docs
weight: 287
url: /de/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) Funktion


Ersetzt alle Vorkommen eines Werts durch einen neuen Wert in einem [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der Span, der inplace geändert wird |
| oldValue | const T\& | Der zu suchende und zu ersetzende Wert |
| newValue | const T\& | Der neue Wert, mit dem oldValue ersetzt wird |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) Funktion


Kopiert Elemente von der Quelle zum Ziel und ersetzt dabei angegebene Werte während des Kopierens.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Quell-[ReadOnlySpan](../../system/readonlyspan/) zum Kopieren |
| destination | [Span](../../system/span/)\<T\>\& | Der Ziel-[Span](../../system/span/) zum Kopieren |
| oldValue | const T\& | Der Wert, nach dem gesucht und der während des Kopierens ersetzt werden soll |
| newValue | const T\& | Der neue Wert, mit dem oldValue ersetzt wird |

## Siehe auch

* Klasse [Span](../../system/span/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)
---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides für C++ API Referenz
description: Findet das letzte Vorkommen eines Elements, ausgenommen drei angegebene Werte, innerhalb eines Span.
type: docs
weight: 235
url: /de/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen drei angegebene Werte, innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |
| value2 | const T\& | Der dritte auszuschließende Wert |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen drei angegebene Werte, innerhalb eines veränderbaren Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |
| value2 | const T\& | Der dritte auszuschließende Wert |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen zwei angegebene Werte, innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen zwei angegebene Werte, innerhalb eines veränderbaren Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen eines angegebenen Wertes, innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value | const T\& | Der auszuschließende Wert |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen eines angegebenen Wertes, innerhalb eines veränderbaren Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| value | const T\& | Der auszuschließende Wert |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen Werte aus einer Sequenz, innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die Sequenz der auszuschließenden Werte |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen Werte aus einer Sequenz, innerhalb eines veränderbaren Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die Sequenz der auszuschließenden Werte |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) Funktion


Findet das letzte Vorkommen eines Elements, ausgenommen Werte aus einer veränderbaren Sequenz, innerhalb eines veränderbaren Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| values | const [Span](../../system/span/)\<T\>\& | Die Sequenz der auszuschließenden Werte |

### Rückgabewert

Der nullbasierte Index des zuletzt nicht ausgeschlossen-Elements oder -1, wenn kein Treffer gefunden wurde

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)
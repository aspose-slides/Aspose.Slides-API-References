---
title: StartsWith()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob der Span mit dem angegebenen Wert beginnt.
type: docs
weight: 352
url: /de/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) Funktion

Überprüft, ob der Span mit dem angegebenen Wert beginnt.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu prüfende Span |
| value | const T\& | Der Wert, der am Anfang des Span geprüft werden soll |

### Rückgabewert

true, wenn der Span mit dem Wert beginnt, sonst false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Überprüft, ob der Span mit dem angegebenen Wert-Span beginnt.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu prüfende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, der die Werte enthält, die am Anfang geprüft werden sollen |

### Rückgabewert

true, wenn der Span mit dem Wert-Span beginnt, sonst false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Überprüft, ob der veränderbare Span mit dem angegebenen schreibgeschützten Wert-Span beginnt.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu prüfende veränderbare Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der schreibgeschützte Span, der die zu prüfenden Werte enthält |

### Rückgabewert

true, wenn der Span mit dem Wert-Span beginnt, sonst false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) Funktion

Überprüft, ob der schreibgeschützte Span mit dem angegebenen veränderbaren Wert-Span beginnt.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu prüfende schreibgeschützte Span |
| value | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, der die zu prüfenden Werte enthält |

### Rückgabewert

true, wenn der Span mit dem Wert-Span beginnt, sonst false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) Funktion

Überprüft, ob der Zeichen-Span mit dem angegebenen Wert-Span unter Verwendung von StringComparison beginnt.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu prüfende Zeichen-Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der Zeichen-Span, der die zu prüfenden Werte enthält |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Der Typ des durchzuführenden Stringvergleichs |

### Rückgabewert

true, wenn der Span mit dem Wert-Span beginnt, sonst false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) Funktion

Überprüft, ob ein String-Span mit dem angegebenen Zeichen-Array beginnt.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Der zu prüfende String-Span |
| val | const char16_t * | Das Zeichen-Array, das am Anfang geprüft werden soll |

### Rückgabewert

true, wenn der Span mit dem Zeichen-Array beginnt, sonst false

## Siehe auch

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
---
title: LastIndexOf()
second_title: Aspose.Slides C++ API-referencia
description: Megkeresi egy szekvencia utolsó előfordulását egy spanben.
type: docs
weight: 209
url: /hu/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Finds the last occurrence of a sequence within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő sorozat |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Finds the last occurrence of a single value within a span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const T\& | A keresendő érték |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Finds the last occurrence of a sequence within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő sorozat |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

Finds the last occurrence of a single value within a mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const T\& | A keresendő érték |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Finds the last occurrence of a value within a span using specified string comparison.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A keresendő érték |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A végrehajtandó karakterlánc-összehasonlítás típusa |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1, ha nem található

## Lásd még

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
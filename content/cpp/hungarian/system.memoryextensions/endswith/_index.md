---
title: EndsWith()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy egy ReadOnlySpan<T> egyetlen értékkel végződik-e.
type: docs
weight: 131
url: /hu/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

Megállapítja, hogy a ReadOnlySpan<T> egyetlen értékkel végződik-e.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A vizsgálandó span |
| value | const T\& | A span végén ellenőrzendő érték |

### Visszatérési érték

true, ha a span a megadott értékkel végződik, különben false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Megállapítja, hogy a ReadOnlySpan<T> egy másik ReadOnlySpan<T>-vel végződik-e.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A vizsgálandó span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A célspan végén ellenőrzendő span |

### Visszatérési érték

true, ha a span a megadott értékspannel végződik, különben false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Megállapítja, hogy a Span<T> egy ReadOnlySpan<T>-vel végződik-e.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A vizsgálandó span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A célspan végén ellenőrzendő span |

### Visszatérési érték

true, ha a span a megadott értékspannel végződik, különben false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

Megállapítja, hogy a ReadOnlySpan<T> egy Span<T>-vel végződik-e.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A vizsgálandó span |
| value | const [Span](../../system/span/)\<T\>\& | A célspan végén ellenőrzendő span |

### Visszatérési érték

true, ha a span a megadott értékspannel végződik, különben false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

Megállapítja, hogy a Span<T> egy másik Span<T>-vel végződik-e.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A vizsgálandó span |
| value | const [Span](../../system/span/)\<T\>\& | A célspan végén ellenőrzendő span |

### Visszatérési érték

true, ha a span a megadott értékspannel végződik, különben false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Megállapítja, hogy a ReadOnlySpan<char16_t> a megadott értékkel végződik-e a StringComparison használatával.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A vizsgálandó span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A span végén ellenőrzendő érték |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A használandó karakterlánc-összehasonlítás típusa |

### Visszatérési érték

true, ha a span a megadott értékkel végződik, különben false

## Lásd még

* Enum [StringComparison](../../system/stringcomparison/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtere [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)
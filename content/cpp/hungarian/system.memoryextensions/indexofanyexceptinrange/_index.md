---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides C++ API referenciája
description: Megkeresi az első elem indexét, amely kívül esik a megadott tartományon egy ReadOnlySpan<T>-ban
type: docs
weight: 183
url: /hu/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény

Megkeresi az első elem indexét, amely kívül esik a megadott tartományon egy ReadOnlySpan<T>-ban

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| lowInclusive | const T\& | A tartomány alsó határa (inkluzív) |
| highInclusive | const T\& | A tartomány felső határa (inkluzív) |

### Visszatérési érték

A nulla-alapú index az első elemre, amely a tartományon kívül van, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) függvény

Megkeresi az első elem indexét, amely kívül esik a megadott tartományon egy Span<T>-ban

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| lowInclusive | const T\& | A tartomány alsó határa (inkluzív) |
| highInclusive | const T\& | A tartomány felső határa (inkluzív) |

### Visszatérési érték

A nulla-alapú index az első elemre, amely a tartományon kívül van, vagy -1, ha nem található

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)
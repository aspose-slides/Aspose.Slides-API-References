---
title: Compare()
second_title: Aspose.Slides C++ API referencia
description: Két okos mutatót hasonlít össze.
type: docs
weight: 1
url: /hu/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) függvény

Összehasonlít két okos mutatót.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első okos mutató típusa |
| U | A második okos mutató típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Az első okos mutató |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | A második okos mutató |

### Visszatérési érték

[Comparison](../../system/comparison/) eredmény (0 ha egyenlő, -1 ha a < b, 1 ha a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) függvény

Összehasonlít két aritmetikai értéket.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Aritmetikai típus |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const T\& | Az első érték |
| b | const T\& | A második érték |

### Visszatérési érték

[Comparison](../../system/comparison/) eredmény (0 ha egyenlő, -1 ha a < b, 1 ha a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) függvény

Összehasonlít egy okos mutatót egy értékkel.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az okos mutató által mutatott típus |
| U | Az érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Okos mutató |
| b | const U\& | Érték |

### Visszatérési érték

[Comparison](../../system/comparison/) eredmény (0 ha egyenlő, -1 ha a < b, 1 ha a > b)

## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Névtér [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)
---
title: Compare()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává dva chytré ukazatele.
type: docs
weight: 1
url: /cs/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) funkce


Porovnává dva chytré ukazatele.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvního chytrého ukazatele |
| U | Typ druhého chytrého ukazatele |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | První chytrý ukazatel |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Druhý chytrý ukazatel |

### Návratová hodnota

[Comparison](../../system/comparison/) výsledek (0 pokud jsou stejné, -1 pokud a < b, 1 pokud a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) funkce


Porovnává dvě aritmetické hodnoty.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Aritmetický typ |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const T\& | První hodnota |
| b | const T\& | Druhá hodnota |

### Návratová hodnota

[Comparison](../../system/comparison/) výsledek (0 pokud jsou stejné, -1 pokud a < b, 1 pokud a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) funkce


Porovnává chytrý ukazatel s hodnotou.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, na který ukazuje chytrý ukazatel |
| U | Typ hodnoty |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Chytrý ukazatel |
| b | const U\& | Hodnota |

### Návratová hodnota

[Comparison](../../system/comparison/) výsledek (0 pokud jsou stejné, -1 pokud a < b, 1 pokud a > b)

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)
---
title: Compare()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Porównuje dwa wskaźniki inteligentne.
type: docs
weight: 1
url: /pl/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) funkcja

Porównuje dwa wskaźniki inteligentne.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ pierwszego wskaźnika inteligentnego |
| U | Typ drugiego wskaźnika inteligentnego |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pierwszy wskaźnik inteligentny |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Drugi wskaźnik inteligentny |

### Wartość zwracana

[Comparison](../../system/comparison/) wynik (0 jeśli równe, -1 jeśli a < b, 1 jeśli a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) funkcja

Porównuje dwie wartości arytmetyczne.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ arytmetyczny |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const T\& | Pierwsza wartość |
| b | const T\& | Druga wartość |

### Wartość zwracana

[Comparison](../../system/comparison/) wynik (0 jeśli równe, -1 jeśli a < b, 1 jeśli a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) funkcja

Porównuje wskaźnik inteligentny z wartością.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, na który wskazuje wskaźnik inteligentny |
| U | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Wskaźnik inteligentny |
| b | const U\& | Wartość |

### Wartość zwracana

[Comparison](../../system/comparison/) wynik (0 jeśli równe, -1 jeśli a < b, 1 jeśli a > b)

## Zobacz także

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)
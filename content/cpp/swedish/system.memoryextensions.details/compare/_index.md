---
title: Compare()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två smarta pekare.
type: docs
weight: 1
url: /sv/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) funktion


Jämför två smarta pekare.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av första smarta pekare |
| U | Typ av andra smarta pekare |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Första smarta pekaren |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Andra smarta pekaren |

### Returvärde

[Comparison](../../system/comparison/) resultat (0 om lika, -1 om a < b, 1 om a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) funktion


Jämför två aritmetiska värden.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Aritmetisk typ |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const T\& | Första värdet |
| b | const T\& | Andra värdet |

### Returvärde

[Comparison](../../system/comparison/) resultat (0 om lika, -1 om a < b, 1 om a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) funktion


Jämför en smart pekare med ett värde.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ som pekas på av smart pekare |
| U | Typ av värde |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pekare |
| b | const U\& | Värde |

### Returvärde

[Comparison](../../system/comparison/) resultat (0 om lika, -1 om a < b, 1 om a > b)

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)
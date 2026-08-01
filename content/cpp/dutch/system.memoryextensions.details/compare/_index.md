---
title: Compare()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt twee smart pointers.
type: docs
weight: 1
url: /nl/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) functie


Vergelijkt twee smart pointers.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de eerste smart pointer |
| U | Type van de tweede smart pointer |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Eerste smart pointer |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Tweede smart pointer |

### Retourwaarde

[Comparison](../../system/comparison/) resultaat (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) functie


Vergelijkt twee rekenkundige waarden.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Arithmetisch type |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const T\& | Eerste waarde |
| b | const T\& | Tweede waarde |

### Retourwaarde

[Comparison](../../system/comparison/) resultaat (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) functie


Vergelijkt een smart pointer met een waarde.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type waarnaar de smart pointer verwijst |
| U | Type van de waarde |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer |
| b | const U\& | Waarde |

### Retourwaarde

[Comparison](../../system/comparison/) resultaat (0 if equal, -1 if a < b, 1 if a > b)

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)
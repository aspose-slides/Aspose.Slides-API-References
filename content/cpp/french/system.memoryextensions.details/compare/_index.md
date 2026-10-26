---
title: Compare()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare deux pointeurs intelligents.
type: docs
weight: 1
url: /fr/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) fonction


Compare deux pointeurs intelligents.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du premier pointeur intelligent |
| U | Type du second pointeur intelligent |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Premier pointeur intelligent |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Second pointeur intelligent |

### Valeur de retour

[Comparison](../../system/comparison/) résultat (0 si égal, -1 si a < b, 1 si a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) fonction


Compare deux valeurs arithmétiques.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type arithmétique |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const T\& | Première valeur |
| b | const T\& | Seconde valeur |

### Valeur de retour

[Comparison](../../system/comparison/) résultat (0 si égal, -1 si a < b, 1 si a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) fonction


Compare un pointeur intelligent à une valeur.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type pointé par le pointeur intelligent |
| U | Type de la valeur |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pointeur intelligent |
| b | const U\& | Valeur |

### Valeur de retour

[Comparison](../../system/comparison/) résultat (0 si égal, -1 si a < b, 1 si a > b)

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)
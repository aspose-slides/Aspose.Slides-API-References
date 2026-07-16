---
title: StartsWith()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si la séquence commence par la valeur spécifiée.
type: docs
weight: 352
url: /fr/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) function


Vérifie si la séquence commence par la valeur spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la séquence |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence à vérifier |
| value | const T\& | La valeur à vérifier au début de la séquence |

### Valeur de retour

true si la séquence commence par la valeur, false sinon

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Vérifie si la séquence commence par la séquence de valeur spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments des séquences |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence à vérifier |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence contenant les valeurs à vérifier au début |

### Valeur de retour

true si la séquence commence par la séquence de valeur, false sinon

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Vérifie si la séquence mutable commence par la séquence de valeur en lecture seule spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments des séquences |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La séquence mutable à vérifier |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence en lecture seule contenant les valeurs à vérifier |

### Valeur de retour

true si la séquence commence par la séquence de valeur, false sinon

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function


Vérifie si la séquence en lecture seule commence par la séquence de valeur mutable spécifiée.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments des séquences |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La séquence en lecture seule à vérifier |
| value | const [Span](../../system/span/)\<T\>\& | La séquence mutable contenant les valeurs à vérifier |

### Valeur de retour

true si la séquence commence par la séquence de valeur, false sinon

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Vérifie si la séquence de caractères commence par la séquence de valeur spécifiée en utilisant la comparaison de chaînes.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La séquence de caractères à vérifier |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La séquence de caractères contenant les valeurs à vérifier |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Le type de comparaison de chaînes à effectuer |

### Valeur de retour

true si la séquence commence par la séquence de valeur, false sinon

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) function


Vérifie si une séquence de chaînes commence par le tableau de caractères spécifié.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | La séquence de chaînes à vérifier |
| val | const char16_t * | Le tableau de caractères à vérifier au début |

### Valeur de retour

true si la séquence commence par le tableau de caractères, false sinon

## Voir aussi

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Classe [String](../../system/string/)
* Espace de noms [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
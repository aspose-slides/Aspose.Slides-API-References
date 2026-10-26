---
title: Contains()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si une plage en lecture seule contient une valeur spécifique.
type: docs
weight: 40
url: /fr/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) fonction

Vérifie si une plage en lecture seule contient une valeur spécifique.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La plage dans laquelle chercher |
| value | const T\& | La valeur à rechercher |

### Valeur de retour

true si la valeur est trouvée dans la plage, false sinon

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) fonction

Vérifie si une plage mutable contient une valeur spécifique.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la plage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La plage mutable dans laquelle chercher |
| value | const T\& | La valeur à rechercher |

### Valeur de retour

true si la valeur est trouvée dans la plage, false sinon

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonction

Vérifie si une plage de caractères contient une autre plage de caractères avec les règles de comparaison spécifiées.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La plage dans laquelle chercher |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | La plage à rechercher |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Le type de comparaison de chaînes à effectuer |

### Valeur de retour

true si la valeur est trouvée dans la plage, false sinon

## Voir aussi

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
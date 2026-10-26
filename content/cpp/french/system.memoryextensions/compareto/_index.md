---
title: CompareTo()
second_title: Référence de l'API Aspose.Slides for C++
description: Compare deux spans de caractères avec les règles de comparaison de chaînes spécifiées.
type: docs
weight: 404
url: /fr/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fonction

Compare deux spans de caractères avec les règles de comparaison de chaînes spécifiées.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Le premier span de caractères |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Le deuxième span de caractères |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Le type de comparaison de chaînes à effectuer |

### Valeur de retour

Valeur négative si span < other, zéro si égal, positive si span > other

## Voir aussi

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Espace de noms [System::MemoryExtensions](../)
* Bibliothèque [Aspose.Slides](../../)
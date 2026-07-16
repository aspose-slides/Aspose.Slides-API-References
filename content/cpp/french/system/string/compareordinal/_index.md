---
title: CompareOrdinal()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare deux chaînes en mode ordinal avec les opérateurs inférieur, égal et supérieur.
type: docs
weight: 833
url: /fr/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) méthode

Compare les deux chaînes en utilisant le mode ordinal.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont égales, valeur positive sinon.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) méthode

Compare les deux chaînes en utilisant le mode ordinal.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Première chaîne à comparer. |
| indexA | int | Début de la sous-chaîne de la première chaîne. |
| strB | const [String](../)\& | Deuxième chaîne à comparer. |
| indexB | int | Début de la sous-chaîne de la deuxième chaîne. |
| length | int | Nombre de caractères à comparer. |

### Valeur de retour

Valeur négative si la première sous-chaîne est inférieure à la seconde, zéro si elles sont égales, valeur positive sinon.

## Voir aussi

* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
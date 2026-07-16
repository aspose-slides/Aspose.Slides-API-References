---
title: CompareOptions
second_title: Référence de l'API Aspose.Slides pour C++
description: Options de comparaison de chaînes.
type: docs
weight: 430
url: /fr/system.globalization/compareoptions/
---
## CompareOptions enum

[String](../../system/string/) options de comparaison.

```cpp
enum class CompareOptions : int32_t
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucune option spéciale. |
| IgnoreCase | 1 | Ignorer la casse. |
| IgnoreNonSpace | 2 | Ignorer les caractères de combinaison non espacés, par ex. les diacritiques. |
| IgnoreSymbols | 4 | Inclure les espaces, les signes de ponctuation, etc. |
| IgnoreKanaType | 8 | Ignorer le type kana (japonais). |
| IgnoreWidth | 16 | Ignorer la largeur des caractères lors de la comparaison de chaînes. |
| OrdinalIgnoreCase | 268435456 | Comparaison ordinale avec différence de casse ignorée. |
| StringSort | 536870912 | Utiliser l'algorithme de tri des chaînes pour comparer les caractères. |
| Ordinal | 1073741824 | Comparer les codes UTF directement pour la première comparaison. |

## Voir aussi

* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)
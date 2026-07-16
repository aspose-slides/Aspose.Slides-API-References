---
title: IsStringLiteral
second_title: Référence de l'API Aspose.Slides pour C++
description: Magie de template pour vérifier si un type est une littérale de chaîne.
type: docs
weight: 1704
url: /fr/system/isstringliteral/
---
## IsStringLiteral struct


Magie de template pour vérifier si un type est une littérale de chaîne.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### Paramètres du template

| Paramètre | Description |
| --- | --- |
| T | type vérifié. |
| CharT | type de caractère à vérifier. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)
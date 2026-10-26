---
title: IsStringPointer
second_title: Référence de l'API Aspose.Slides pour C++
description: Magie de modèle pour vérifier si un type est un pointeur vers une chaîne de caractères.
type: docs
weight: 1717
url: /fr/system/isstringpointer/
---
## IsStringPointer struct

Magie de modèle pour vérifier si un type est un pointeur vers une chaîne de caractères.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type vérifié. |
| CharT | type de caractère à vérifier. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)
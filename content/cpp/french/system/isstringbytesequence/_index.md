---
title: IsStringByteSequence
second_title: Référence de l'API Aspose.Slides pour C++
description: Magie de modèle pour vérifier si un type est une séquence de caractères de chaîne.
type: docs
weight: 1691
url: /fr/system/isstringbytesequence/
---
## IsStringByteSequence struct


Magie de modèle pour vérifier si un type est une séquence de caractères de chaîne.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | type vérifié. |
| CharT | type de caractère à vérifier. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)
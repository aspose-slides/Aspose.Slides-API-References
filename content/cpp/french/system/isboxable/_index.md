---
title: IsBoxable
second_title: Référence de l'API Aspose.Slides pour C++
description: Prédicat de modèle qui vérifie si l'encapsulation du type spécifié est prise en charge.
type: docs
weight: 1639
url: /fr/system/isboxable/
---
## IsBoxable struct

Prédicat de modèle qui vérifie si l’encapsulation du type spécifié est prise en charge.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Le type à vérifier |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)
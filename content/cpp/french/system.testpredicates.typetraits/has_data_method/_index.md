---
title: has_data_method
second_title: Référence de l'API Aspose.Slides pour C++
description: "Vérifie si un type possède la méthode data(). Si c’est le cas, il hérite de std::true_type, sinon il hérite de std::false_type."
type: docs
weight: 1
url: /fr/system.testpredicates.typetraits/has_data_method/
---
## has_data_method struct

Vérifie si un type possède la méthode data(). Si c’est le cas, hérite de std::true_type, sinon il hérite de std::false_type.

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à vérifier. |
| Enable | Argument formel pour que SFINAE fonctionne. |

## Voir aussi

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)
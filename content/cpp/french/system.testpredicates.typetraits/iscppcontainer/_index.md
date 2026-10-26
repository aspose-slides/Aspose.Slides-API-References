---
title: IsCppContainer
second_title: Référence API Aspose.Slides pour C++
description: "Vérifie si un type spécifique est un conteneur de style STL. Pour ce faire, vérifie l'existence des types membres iterator et const_iterator. Si les deux existent, hérite de std::true_type, sinon hérite de std::false_type."
type: docs
weight: 40
url: /fr/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Vérifie si un type spécifique est un conteneur de type STL. Pour ce faire, vérifie l'existence des types membres iterator et const_iterator. Si les deux existent, hérite de std::true_type, sinon hérite de std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à vérifier. |
| Enable | Argument formel pour que SFINAE fonctionne. |

## Voir aussi

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)
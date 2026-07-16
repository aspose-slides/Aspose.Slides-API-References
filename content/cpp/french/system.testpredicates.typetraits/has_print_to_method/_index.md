---
title: has_print_to_method
second_title: Référence de l'API Aspose.Slides pour C++
description: "Vérifie la surcharge de la fonction PrintTo qui accepte le type donné comme premier argument. Si une surcharge existe, hérite de std::true_type, sinon hérite de std::false_type."
type: docs
weight: 27
url: /fr/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Vérifie la surcharge de la fonction PrintTo qui accepte le type donné comme premier argument. Si une surcharge existe, hérite de std::true_type, sinon hérite de std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type à vérifier. |
| Enable | Argument formel pour que le SFINAE fonctionne. |

## Voir aussi

* Espace de noms [System::TestPredicates::TypeTraits](../)
* Bibliothèque [Aspose.Slides](../../)
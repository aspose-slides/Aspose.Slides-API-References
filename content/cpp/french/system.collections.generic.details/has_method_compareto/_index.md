---
title: has_method_compareto
second_title: Référence API Aspose.Slides pour C++
description: "Vérifie si la méthode CompareTo existe dans le type spécifié. Le cas échéant, hérite de std::true_type, sinon hérite de std::false_type. Peut être utilisé dans std::enable_if."
type: docs
weight: 170
url: /fr/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

Vérifie si la méthode CompareTo existe dans le type spécifié. Le cas échéant, hérite de std::true_type, sinon hérite de std::false_type. Peut être utilisé dans std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type à vérifier pour la présence de la méthode Equals. |
| Sfinae | Argument de modèle formel pour que SFINAE fonctionne. |

## Voir aussi

* Espace de noms [System::Collections::Generic::Details](../)
* Bibliothèque [Aspose.Slides](../../)
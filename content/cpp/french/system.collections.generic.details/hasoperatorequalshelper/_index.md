---
title: HasOperatorEqualsHelper()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fonction d'assistance pour déterminer si une classe spécifique possède l'opérateur ==.
type: docs
weight: 235
url: /fr/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) fonction

Fonction d'assistance pour déterminer si une classe spécifique possède l'opérateur ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à vérifier. |
| Dummy | Argument factice pour la magie SFINAE. |

### Valeur de retour

Valeur de std::true_type si l'opérateur == est présent et false sinon.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) fonction

Fonction d'assistance pour déterminer si une classe spécifique possède l'opérateur ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Valeur de retour

Valeur de std::true_type si l'opérateur == est présent et false sinon.

## Voir aussi

* Espace de noms [System::Collections::Generic::Details](../)
* Bibliothèque [Aspose.Slides](../../)
---
title: ComparerAdapter
second_title: Aspose.Slides pour C++ Référence API
description: Adaptateur pour utiliser IComparer dans un environnement STL. Utilise IComparer si défini ; sinon, utilise l'opérateur < (si disponible) ou renvoie false (sinon).
type: docs
weight: 638
url: /fr/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adaptateur pour utiliser [IComparer](../icomparer/) dans un environnement STL. Utilise [IComparer](../icomparer/) si défini ; sinon, utilise l'opérateur < (si disponible) ou renvoie false (sinon).

```cpp
template<class T>class ComparerAdapter
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à comparer. |

## Méthodes

| Méthode | Description |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Construit l'adaptateur sans aucun comparateur disponible. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Construit l'adaptateur. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Fonction [Comparison](../../system/comparison/) pour les types avec l'opérateur < disponible. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Fonction [Comparison](../../system/comparison/) pour les types sans opérateur < disponible. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Définit l'objet comparateur. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)
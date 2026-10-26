---
title: EqualityComparerAdapter
second_title: Référence de l'API Aspose.Slides pour C++
description: "Adaptateur permettant d'utiliser IEqualityComparer avec des collections et algorithmes de type STL. Utilise IEqualityComparer, si défini. Sinon, utilise l'opérateur ==, Object::Equals ou T::Equals, selon ce qui est disponible."
type: docs
weight: 664
url: /fr/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter structure


Adaptateur permettant d'utiliser [IEqualityComparer](../iequalitycomparer/) avec des collections et algorithmes de style STL. Utilise [IEqualityComparer](../iequalitycomparer/), si défini. Sinon, utilise l'opérateur ==, [Object::Equals](../../system/object/equals/) ou T::Equals, selon ce qui est disponible.

```cpp
template<class T>class EqualityComparerAdapter
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type comparé. |
## Méthodes

| Méthode | Description |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Crée un adaptateur n'utilisant aucun comparateur. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Crée un adaptateur avec le comparateur fourni. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Compare deux objets. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Définit le comparateur. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)
---
title: EqualityComparerHashAdapter
second_title: Référence API Aspose.Slides pour C++
description: Adaptateur pour utiliser IEqualityComparer pour le hachage. Utilise l'objet comparateur, s'il est défini ; sinon, utilise la méthode de hachage disponible sélectionnée à l'aide de la structure DictionaryHashSelector.
type: docs
weight: 677
url: /fr/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter structure


Adaptateur pour utiliser [IEqualityComparer](../iequalitycomparer/) pour le hachage. Utilise l'objet comparateur, s'il est défini ; sinon, utilise la méthode de hachage disponible sélectionnée à l'aide de la structure [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Hashed | type. |
## Méthodes

| Méthode | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Crée un adaptateur sans comparateur à utiliser. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Crée un adaptateur avec le comparateur donné à utiliser. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Calcule la valeur de hachage. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Définit le comparateur à utiliser. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)
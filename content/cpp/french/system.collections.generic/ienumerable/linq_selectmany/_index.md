---
title: LINQ_SelectMany()
second_title: Référence de l'API Aspose.Slides for C++
description: Projette chaque élément d'une séquence et combine les séquences résultantes en une seule séquence.
type: docs
weight: 300
url: /fr/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) méthode

Projette chaque élément d'une séquence et combine les séquences résultantes en une seule séquence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ResultType | Le type de la valeur renvoyée par le **selector**. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Une fonction de transformation. |

### Valeur de retour

Une [IEnumerable](../) qui contient le résultat de l'appel d'une fonction de projection un-à-plusieurs sur chaque élément de la séquence d'entrée.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) méthode

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)
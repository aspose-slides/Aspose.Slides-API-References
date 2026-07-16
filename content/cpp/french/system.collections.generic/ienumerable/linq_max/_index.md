---
title: LINQ_Max()
second_title: Référence de l'API Aspose.Slides pour C++
description: Appelle une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur maximale obtenue.
type: docs
weight: 339
url: /fr/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) méthode

Appelle une fonction de transformation sur chaque élément d’une séquence générique et renvoie la valeur maximale obtenue.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| ResultType | Le type de la valeur renvoyée par le sélecteur. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Une fonction de transformation à appliquer à chaque élément. |

### Valeur de retour

La valeur maximale dans la séquence.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) méthode

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Voir aussi

* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)
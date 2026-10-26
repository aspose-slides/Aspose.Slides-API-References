---
title: LINQ_Min()
second_title: Référence de l'API Aspose.Slides pour C++
description: Applique une fonction de transformation à chaque élément d'une séquence générique et renvoie la valeur minimale résultante.
type: docs
weight: 326
url: /fr/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) méthode


Applique une fonction de transformation à chaque élément d'une séquence générique et renvoie la valeur minimale résultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ResultType | Le type de la valeur renvoyée par le sélecteur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Une fonction de transformation à appliquer à chaque élément. |

### Valeur de retour

La valeur minimale dans la séquence.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) méthode




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Voir aussi

* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: BinarySearch()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue une recherche binaire dans le tableau trié.
type: docs
weight: 612
url: /fr/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) méthode

Effectue une recherche binaire dans le tableau trié.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Tableau trié dans lequel effectuer la recherche |
| item | const T\& | Élément à rechercher |

### Valeur de retour

Indice de l'élément recherché s'il est trouvé, sinon, un entier négatif qui est le complément à un bit de l'indice du prochain élément supérieur à l'élément recherché ou, s'il n'y a aucun élément supérieur, le complément à un bit du nombre d'éléments du tableau.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) méthode

NON IMPLEMENTÉ.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../)
* Classe [IComparer](../../../system.collections.generic/icomparer/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: CopyTo()
second_title: Référence API Aspose.Slides pour C++
description: Copie les éléments de la liste dans les éléments d'un tableau existant.
type: docs
weight: 209
url: /fr/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) méthode

Copie les éléments de la liste dans les éléments d'un tableau existant.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Tableau de destination. |
| arrayIndex | int | Indice de départ du tableau de destination. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) méthode

Copie tous les éléments dans les éléments d'un tableau existant.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) dans lequel copier les éléments. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) méthode

Copie les éléments à partir de l'index spécifié dans les éléments d'un tableau existant.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Un index basé à 0 de l'élément dans la liste représentée par l'objet courant à partir duquel commencer la copie |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) dans lequel copier les éléments. |
| arrayIndex | int | Position de départ dans le tableau de destination. |
| count | int | Nombre d'éléments à copier. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [List](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: LINQ_Select()
second_title: Référence de l'API Aspose.Slides pour C++
description: Transforme les éléments d'une séquence.
type: docs
weight: 248
url: /fr/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) méthode

Transforme les éléments d'une séquence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ResultType | Le type de la valeur renvoyée par le **selector**. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Une fonction de transformation. |

### Valeur de retour

Un [IEnumerable](../) qui contient les éléments renvoyés par la fonction **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) méthode

Transforme chaque élément d'une séquence en une nouvelle forme en incorporant l'indice de l'élément.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ResultType | Le type de la valeur renvoyée par le **selector**. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Une fonction de transformation. |

### Valeur de retour

Un [IEnumerable](../) qui contient les éléments renvoyés par la fonction **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) méthode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) méthode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Espace de noms [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
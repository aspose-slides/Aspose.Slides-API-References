---
title: CopyTo()
second_title: Référence API Aspose.Slides pour C++
description: Copie tous les éléments du tableau actuel vers le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l'argument arrayIndex.
type: docs
weight: 118
url: /fr/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) méthode

Copie tous les éléments du tableau actuel dans le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l’indice spécifié par l’argument arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Tableau de destination |
| arrayIndex | int | Indice dans le tableau de destination où commencer à insérer les éléments copiés à |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const méthode

Copie tous les éléments du tableau actuel dans le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l’indice spécifié par l’argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| DstType | Type des éléments dans le tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| dstIndex | **int64_t** | Indice dans le tableau de destination où commencer à insérer les éléments copiés à |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const méthode

Copie tous les éléments du tableau actuel dans la vue du tableau de destination spécifiée. Les éléments sont insérés dans la vue du tableau de destination à partir de l’indice spécifié par l’argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| DstType | Type des éléments dans la vue du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vue du tableau de destination |
| dstIndex | **int64_t** | Indice dans la vue du tableau de destination où commencer à insérer les éléments copiés à |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const méthode

Copie un nombre spécifié d’éléments du tableau actuel à partir d’une position spécifiée vers le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l’indice spécifié par l’argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| DstType | Type des éléments dans le tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| srcIndex | **int64_t** | Indice dans le tableau source où commencer à copier les éléments à |
| dstIndex | **int64_t** | Indice dans le tableau de destination où commencer à insérer les éléments copiés à |
| count | **int64_t** | Nombre d’éléments à copier |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const méthode

Copie un nombre spécifié d’éléments du tableau actuel à partir d’une position spécifiée vers la vue du tableau de destination spécifiée. Les éléments sont insérés dans la vue du tableau de destination à partir de l’indice spécifié par l’argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| DstType | Type des éléments dans la vue du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vue du tableau de destination |
| srcIndex | **int64_t** | Indice dans le tableau source où commencer à copier les éléments à |
| dstIndex | **int64_t** | Indice dans la vue du tableau de destination où commencer à insérer les éléments copiés à |
| count | **int64_t** | Nombre d’éléments à copier |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
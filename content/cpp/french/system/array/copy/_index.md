---
title: Copy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Copie le nombre spécifié d'éléments du tableau source vers le tableau de destination.
type: docs
weight: 729
url: /fr/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) méthode


Copie le nombre spécifié d'éléments du tableau source vers le tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) méthode


Copie le nombre spécifié d'éléments de la vue du tableau source vers le tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vue du tableau source |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) méthode


Copie le nombre spécifié d'éléments du tableau source vers la vue du tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| dstArray | System::Details::ArrayView\<DstType\> | Vue du tableau de destination |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) méthode


Copie le nombre spécifié d'éléments de la vue du tableau source vers la vue du tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vue du tableau source |
| dstArray | System::Details::ArrayView\<DstType\> | Vue du tableau de destination |
| count | **int64_t** | Le nombre d' éléments à copier |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) méthode


Copie le nombre spécifié d'éléments du tableau sur la pile vers le tableau de destination.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Tableau sur la pile source |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) méthode


Copie le nombre spécifié d'éléments du tableau source vers le tableau sur la pile de destination.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Tableau sur la pile de destination |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) méthode


Copie le nombre spécifié d'éléments du tableau sur la pile source vers le tableau sur la pile de destination.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Tableau sur la pile source |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Tableau sur la pile de destination |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments du tableau source à partir de l'index indiqué vers la position indiquée dans le tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments du tableau source |
| DstType | Type des éléments du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| srcIndex | **int64_t** | Index du tableau source désignant le début de la plage d'éléments à copier |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| dstIndex | **int64_t** | Index du tableau de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments de la vue du tableau source à partir de l'index indiqué vers la position indiquée dans le tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments de la vue du tableau source |
| DstType | Type des éléments du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vue du tableau source |
| srcIndex | **int64_t** | Index de la vue du tableau source désignant le début de la plage d'éléments à copier |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| dstIndex | **int64_t** | Index du tableau de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments du tableau source à partir de l'index indiqué vers la position indiquée dans la vue du tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments du tableau source |
| DstType | Type des éléments de la vue du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| srcIndex | **int64_t** | Index du tableau source désignant le début de la plage d'éléments à copier |
| dstArray | System::Details::ArrayView\<DstType\> | Vue du tableau de destination |
| dstIndex | **int64_t** | Index de la vue du tableau de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments de la vue du tableau source à partir de l'index indiqué vers la position indiquée dans la vue du tableau de destination.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments de la vue du tableau source |
| DstType | Type des éléments de la vue du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vue du tableau source |
| srcIndex | **int64_t** | Index de la vue du tableau source désignant le début de la plage d'éléments à copier |
| dstArray | System::Details::ArrayView\<DstType\> | Vue du tableau de destination |
| dstIndex | **int64_t** | Index de la vue du tableau de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments du tableau sur la pile source à partir de l'index indiqué vers la position indiquée dans le tableau de destination.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments du tableau sur la pile source |
| DstType | Type des éléments du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Tableau sur la pile source |
| srcIndex | **int64_t** | Index du tableau sur la pile source désignant le début de la plage d'éléments à copier |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| dstIndex | **int64_t** | Index du tableau de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments du tableau source à partir de l'index indiqué vers la position indiquée dans le tableau sur la pile de destination.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments du tableau source |
| DstType | Type des éléments du tableau sur la pile de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| srcIndex | **int64_t** | Index du tableau source désignant le début de la plage d'éléments à copier |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Tableau sur la pile de destination |
| dstIndex | **int64_t** | Index du tableau sur la pile de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments du tableau sur la pile source à partir de l'index indiqué vers la position indiquée dans le tableau sur la pile de destination.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments du tableau sur la pile source |
| DstType | Type des éléments du tableau sur la pile de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Tableau sur la pile source |
| srcIndex | **int64_t** | Index du tableau sur la pile source désignant le début de la plage d'éléments à copier |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Tableau sur la pile de destination |
| dstIndex | **int64_t** | Index du tableau sur la pile de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) méthode


Copie un nombre spécifié d'éléments de la vue du tableau source à partir de l'index indiqué vers la position indiquée dans le tableau sur la pile de destination.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type des éléments du tableau sur la pile source |
| DstType | Type des éléments du tableau sur la pile de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Vue du tableau source |
| srcIndex | **int64_t** | Index de la vue du tableau source désignant le début de la plage d'éléments à copier |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Tableau sur la pile de destination |
| dstIndex | **int64_t** | Index du tableau sur la pile de destination où commencer l'insertion des éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
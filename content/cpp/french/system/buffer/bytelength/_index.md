---
title: ByteLength()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié.
type: docs
weight: 14
url: /fr/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) méthode


Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Un tableau |

### Valeur de retour

Le nombre d'octets occupés par tous les éléments du tableau spécifié

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) méthode


Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la vue de tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Une vue de tableau |

### Valeur de retour

Le nombre d'octets occupés par tous les éléments de la vue de tableau spécifiée

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) méthode


Détermine le nombre d'octets occupés par tous les éléments du tableau spécifié.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau empilé |
| N | La taille du tableau empilé |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Un tableau empilé |

### Valeur de retour

Le nombre d'octets occupés par tous les éléments du tableau empilé spécifié

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
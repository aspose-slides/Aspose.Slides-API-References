---
title: BlockCopy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Copie un nombre spécifié d'octets du tampon source vers le tampon de destination.
type: docs
weight: 1
url: /fr/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) méthode


Copie un nombre spécifié d'octets du tampon source vers le tampon de destination.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const **uint8_t** * | Pointeur vers le tampon source |
| srcOffset | int | Un décalage en octets dans le tampon source à partir duquel la copie commence |
| dst | **uint8_t** * | Pointeur vers le tampon de destination |
| dstOffset | int | Un décalage en octets dans le tampon de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments du tableau source |
| TDst | Le type des éléments du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Le tableau source |
| srcOffset | int | Un décalage en octets dans le tableau source tho à partir duquel la copie commence |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Le tableau de destination |
| dstOffset | int | Un décalage en octets dans le tableau de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) méthode


Interprète deux tableaux spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Le tableau source |
| srcOffset | int | Un décalage en octets dans le tableau source tho à partir duquel la copie commence |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Le tableau de destination |
| dstOffset | int | Un décalage en octets dans le tableau de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments de la vue de tableau source |
| TDst | Le type des éléments de la vue de tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | La vue de tableau source |
| srcOffset | int | Un décalage en octets dans la vue de tableau source tho à partir duquel la copie commence |
| dst | const System::Details::ArrayView\<TDst\>\& | La vue de tableau de destination |
| dstOffset | int | Un décalage en octets dans la vue de tableau de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments du tableau source |
| TDst | Le type des éléments de la vue de tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Le tableau source |
| srcOffset | int | Un décalage en octets dans le tableau source tho à partir duquel la copie commence |
| dst | const System::Details::ArrayView\<TDst\>\& | La vue de tableau de destination |
| dstOffset | int | Un décalage en octets dans la vue de tableau de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments de la vue de tableau source |
| TDst | Le type des éléments du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | La vue de tableau source |
| srcOffset | int | Un décalage en octets dans la vue de tableau source tho à partir duquel la copie commence |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Le tableau de destination |
| dstOffset | int | Un décalage en octets dans le tableau de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments du tableau empilé source |
| NS | La taille du tableau empilé source |
| TDst | Le type des éléments du tableau empilé de destination |
| ND | La taille du tableau empilé de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Le tableau empilé source |
| srcOffset | int | Un décalage en octets dans le tableau empilé source tho à partir duquel la copie commence |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Le tableau empilé de destination |
| dstOffset | int | Un décalage en octets dans le tableau empilé de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments du tableau source |
| TDst | Le type des éléments du tableau empilé de destination |
| ND | La taille du tableau empilé de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Le tableau source |
| srcOffset | int | Un décalage en octets dans le tableau source tho à partir duquel la copie commence |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Le tableau empilé de destination |
| dstOffset | int | Un décalage en octets dans le tableau empilé de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) méthode


Interprète deux tableaux typés spécifiés comme des tableaux bruts d'octets et copie les données de l'un à l'autre.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TSrc | Le type des éléments du tableau empilé source |
| NS | La taille du tableau empilé source |
| TDst | Le type des éléments du tableau de destination |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Le tableau empilé source |
| srcOffset | int | Un décalage en octets dans le tableau empilé source tho à partir duquel la copie commence |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Le tableau de destination |
| dstOffset | int | Un décalage en octets dans le tableau de destination à partir duquel commencer à insérer les données |
| count | int | Le nombre d'octets à copier |

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Buffer](../)
* Classe [Array](../../array/)
* Classe [ArrayBase](../../arraybase/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
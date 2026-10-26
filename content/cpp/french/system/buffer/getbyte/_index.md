---
title: GetByte()
second_title: Référence API Aspose.Slides pour C++
description: Interprète le tableau typé spécifié comme un tableau d'octets brut et récupère la valeur d'octet à l'offset spécifié.
type: docs
weight: 27
url: /fr/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) méthode


Interprète le tableau typé spécifié comme un tableau d’octets brut et récupère la valeur d’octet à l’offset spécifié.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Le tableau cible |
| index | int | Décalage basé sur zéro de l’octet à récupérer |

### Valeur de retour

La valeur d’octet à l’indice spécifié

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) méthode


Interprète le tableau typé spécifié comme un tableau d’octets brut et récupère la valeur d’octet à l’offset spécifié.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments de la vue du tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Le tableau cible |
| index | int | Décalage basé sur zéro de l’octet à récupérer |

### Valeur de retour

La valeur d’octet à l’indice spécifié

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) méthode


Interprète le tableau typé spécifié comme un tableau d’octets brut et récupère la valeur d’octet à l’offset spécifié.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau de pile |
| N | La taille du tableau de pile |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Le tableau de pile cible |
| index | int | Décalage basé sur zéro de l’octet à récupérer |

### Valeur de retour

La valeur d’octet à l’indice spécifié

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../../array/)
* Classe [Buffer](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
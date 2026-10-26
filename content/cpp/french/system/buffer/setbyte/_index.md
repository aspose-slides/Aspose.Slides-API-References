---
title: SetByte()
second_title: Référence de l'API Aspose.Slides for C++
description: Interprete le tableau typé spécifié comme un tableau d'octets brut et definit la valeur d'octet spécifiée à l'offset d'octet indiqué.
type: docs
weight: 40
url: /fr/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) méthode

Interprète le tableau typé spécifié comme un tableau d’octets brut et définit la valeur d’octet spécifiée à l’offset d’octet indiqué.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Le tableau cible |
| index | int | Offset basé sur zéro de l’octet à définir |
| value | **uint8_t** | La valeur d’octet à définir |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) méthode

Interprète le tableau typé spécifié comme un tableau d’octets brut et définit la valeur d’octet spécifiée à l’offset d’octet indiqué.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | La vue du tableau cible |
| index | int | Offset basé sur zéro de l’octet à définir |
| value | **uint8_t** | La valeur d’octet à définir |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) méthode

Interprète le tableau typé spécifié comme un tableau d’octets brut et définit la valeur d’octet spécifiée à l’offset d’octet indiqué.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau |
| N | La taille du tableau empilé |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Le tableau empilé cible |
| index | int | Offset basé sur zéro de l’octet à définir |
| value | **uint8_t** | La valeur d’octet à définir |

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../../array/)
* Classe [Buffer](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: IndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt de index van de eerste voorkoming van het gespecificeerde item in de array.
type: docs
weight: 131
url: /nl/system/array/indexof/
---
## Array::IndexOf(const T\&) const methode

Bepaalt de index van de eerste voorkoming van het gespecificeerde item in de array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const T\& | Itemindex waarvan de index moet worden bepaald |

### Retourwaarde

[Index](../../index/) van de eerste voorkoming van het gespecificeerde item als het item gevonden is, anders -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) methode

Bepaalt de index van de eerste voorkoming van het opgegeven item in de array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) om te zoeken naar het opgegeven item in |
| value | const [ValueType](../valuetype/)\& | Itemindex waarvan de index moet worden bepaald |

### Retourwaarde

[Index](../../index/) van de eerste voorkoming van het opgegeven item als het item gevonden is, anders -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) methode

Bepaalt de index van de eerste voorkoming van het gespecificeerde item in de array, beginnend vanaf de opgegeven index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) om te zoeken naar het opgegeven item in |
| value | const [ValueType](../valuetype/)\& | Itemindex waarvan de index moet worden bepaald |
| startIndex | int | [Index](../../index/) waarop de zoekopdracht wordt gestart |

### Retourwaarde

[Index](../../index/) van de eerste voorkoming van het gespecificeerde item als het item gevonden is, anders -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) methode

Bepaalt de index van de eerste voorkoming van het gespecificeerde item in een bereik van items van de array, gespecificeerd door de startindex en het aantal elementen in het bereik.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) om te zoeken naar het opgegeven item in |
| value | const [ValueType](../valuetype/)\& | Itemindex waarvan de index moet worden bepaald |
| startIndex | int | [Index](../../index/) waarop de zoekopdracht wordt gestart |
| count | int | Aantal elementen van het bereik waarin gezocht moet worden |

### Retourwaarde

[Index](../../index/) van de eerste voorkoming van het gespecificeerde item als het item gevonden is, anders -1

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Klasse [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
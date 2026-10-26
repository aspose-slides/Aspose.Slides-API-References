---
title: LastIndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt de index van het laatste voorkomen van het opgegeven item in een bereik van items van de array, gespecificeerd door de startindex en het aantal elementen in het bereik.
type: docs
weight: 703
url: /nl/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) methode

Bepaalt de index van het laatste voorkomen van het opgegeven item in een bereik van items van de array, gespecificeerd door de startindex en het aantal elementen in het bereik.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) om het opgegeven item te doorzoeken in |
| value | const [ValueType](../valuetype/)\& | Item-index waarvan de index moet worden bepaald |
| startIndex | int | [Index](../../index/) waarbij de zoekopdracht wordt gestart |
| count | int | Aantal elementen van het bereik waarin gezocht wordt |

### Retourwaarde

[Index](../../index/) van het laatste voorkomen van het opgegeven item als het item wordt gevonden, anders -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) methode

Bepaalt de index van het laatste voorkomen van het opgegeven item in de array, beginnend vanaf de opgegeven index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) om het opgegeven item te doorzoeken in |
| value | const [ValueType](../valuetype/)\& | Item-index waarvan de index moet worden bepaald |
| startIndex | int | [Index](../../index/) waarbij de zoekopdracht wordt gestart |

### Retourwaarde

[Index](../../index/) van het laatste voorkomen van het opgegeven item als het item wordt gevonden, anders -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) methode

Bepaalt de index van het laatste voorkomen van het opgegeven item in de array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) om het opgegeven item te doorzoeken in |
| value | const [ValueType](../valuetype/)\& | Item-index waarvan de index moet worden bepaald |

### Retourwaarde

[Index](../../index/) van het laatste voorkomen van het opgegeven item als het item wordt gevonden, anders -1

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
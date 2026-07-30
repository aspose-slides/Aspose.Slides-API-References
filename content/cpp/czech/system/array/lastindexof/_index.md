---
title: LastIndexOf()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje index posledního výskytu zadané položky v rozsahu položek pole určeném počátečním indexem a počtem prvků v rozsahu.
type: docs
weight: 703
url: /cs/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metoda

Určuje index posledního výskytu zadané položky v rozsahu položek pole určeném počátečním indexem a počtem prvků v rozsahu.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ArrayType | Typ prvků v cílovém poli |
| ValueType | typ položky, která se má v poli hledat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pro hledání zadané položky v |
| value | const [ValueType](../valuetype/)\& | Index položky, který má být určen |
| startIndex | int | [Index](../../index/), od kterého se hledání zahajuje |
| count | int | Počet prvků v rozsahu, ve kterém se hledá |

### Návratová hodnota

[Index](../../index/) posledního výskytu zadané položky, pokud je položka nalezena, jinak -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metoda

Určuje index posledního výskytu zadané položky v poli počínaje od zadaného indexu.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ArrayType | Typ prvků v cílovém poli |
| ValueType | typ položky, která se má v poli hledat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pro hledání zadané položky v |
| value | const [ValueType](../valuetype/)\& | Index položky, který má být určen |
| startIndex | int | [Index](../../index/), od kterého se hledání zahajuje |

### Návratová hodnota

[Index](../../index/) posledního výskytu zadané položky, pokud je položka nalezena, jinak -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metoda

Určuje index posledního výskytu zadané položky v poli.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ArrayType | Typ prvků v cílovém poli |
| ValueType | typ položky, která se má v poli hledat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pro hledání zadané položky v |
| value | const [ValueType](../valuetype/)\& | Index položky, který má být určen |

### Návratová hodnota

[Index](../../index/) posledního výskytu zadané položky, pokud je položka nalezena, jinak -1

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
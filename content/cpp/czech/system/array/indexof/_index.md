---
title: IndexOf()
second_title: Aspose.Slides pro C++ referenci API
description: Určuje index prvního výskytu specifikované položky v poli.
type: docs
weight: 131
url: /cs/system/array/indexof/
---
## Array::IndexOf(const T\&) const metoda

Určuje index prvního výskytu specifikované položky v poli.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const T\& | Index položky, jejíž index má být určen |

### Návratová hodnota

[Index](../../index/) index prvního výskytu specifikované položky, pokud je položka nalezena, jinak -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metoda

Určuje index prvního výskytu specifikované položky v poli.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ArrayType | Typ prvků v cílovém poli |
| ValueType | Typ položky, kterou hledat v poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pro hledání specifikované položky v |
| value | const [ValueType](../valuetype/)\& | Index položky, jejíž index má být určen |

### Návratová hodnota

[Index](../../index/) index prvního výskytu specifikované položky, pokud je položka nalezena, jinak -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metoda

Určuje index prvního výskytu specifikované položky v poli počínaje od zadaného indexu.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ArrayType | Typ prvků v cílovém poli |
| ValueType | Typ položky, kterou hledat v poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pro hledání specifikované položky v |
| value | const [ValueType](../valuetype/)\& | Index položky, jejíž index má být určen |
| startIndex | int | [Index](../../index/) při zahájení hledání |

### Návratová hodnota

[Index](../../index/) index prvního výskytu specifikované položky, pokud je položka nalezena, jinak -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metoda

Určuje index prvního výskytu specifikované položky v rozsahu položek pole určeném počátečním indexem a počtem prvků v rozsahu.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ArrayType | Typ prvků v cílovém poli |
| ValueType | Typ položky, kterou hledat v poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) pro hledání specifikované položky v |
| value | const [ValueType](../valuetype/)\& | Index položky, jejíž index má být určen |
| startIndex | int | [Index](../../index/) při zahájení hledání |
| count | int | Počet prvků v rozsahu, ve kterém se hledá |

### Návratová hodnota

[Index](../../index/) index prvního výskytu specifikované položky, pokud je položka nalezena, jinak -1

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
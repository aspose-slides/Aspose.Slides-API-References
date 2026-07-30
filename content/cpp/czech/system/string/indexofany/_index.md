---
title: IndexOfAny()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledávání znaku dopředu.
type: docs
weight: 638
url: /cs/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Vyhledávání znaku dopředu.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak, který se má hledat. |
| startIndex | int | [Index](../../index/) pozice, od které se má vyhledávání zahájit. |

### Návratová hodnota

[Index](../../index/) první pozice znaku od startIndex nebo -1, pokud není nalezen.

## String::IndexOfAny(const String\&, int) const method


Následně hledá všechny znaky řetězce str v tomto řetězci. Pokud je nalezen první znak, vrátí se jeho pozice, jinak se hledá druhý a tak dále.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) znaků, které se mají hledat. Pořadí znaků je důležité. |
| startIndex | int | Pozice, od které se má vyhledávání zahájit. |

### Návratová hodnota

[Index](../../index/) první nalezený znak nebo -1, pokud nebyl nalezen.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Prohledává celý řetězec podle libovolného z předaných znaků. Porovnává první znak řetězce se všemi znaky v anyOf, potom druhý a tak dále. Vrací index prvního znaku, který odpovídá některému z cílových znaků.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků, které se mají hledat. Pořadí není důležité. |

### Návratová hodnota

[Index](../../index/) prvního odpovídajícího znaku nebo -1, pokud nebyl nalezen.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Prohledává podřetězec podle libovolného z předaných znaků. Porovnává první znak řetězce se všemi znaky v anyOf, potom druhý a tak dále. Vrací index prvního znaku, který odpovídá některému z cílových znaků.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků, které se mají hledat. Pořadí není důležité. |
| startindex | **int32_t** | [Index](../../index/) pozice, od které se má vyhledávání zahájit. |

### Návratová hodnota

[Index](../../index/) prvního odpovídajícího znaku nebo -1, pokud nebyl nalezen.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Prohledává podřetězec podle libovolného z předaných znaků. Porovnává první znak řetězce se všemi znaky v anyOf, potom druhý a tak dále. Vrací index prvního znaku, který odpovídá některému z cílových znaků.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaků, které se mají hledat. Pořadí není důležité. |
| startindex | **int32_t** | [Index](../../index/) pozice, od které se má vyhledávání zahájit. |
| count | **int32_t** | Počet znaků, které se mají prohledat. |

### Návratová hodnota

[Index](../../index/) prvního odpovídajícího znaku nebo -1, pokud nebyl nalezen.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
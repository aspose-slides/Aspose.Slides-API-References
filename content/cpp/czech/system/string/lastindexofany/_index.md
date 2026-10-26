---
title: LastIndexOfAny()
second_title: Aspose.Slides pro C++ API Reference
description: Prohledává celý řetězec zpětně a hledá některý z předaných znaků. Porovnává poslední znak řetězce se všemi znaky v anyOf, poté porovnává předchozí a tak dále. Vrací index první nalezené shody.
type: docs
weight: 664
url: /cs/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method

Prohledává celý řetězec zpětně a hledá některý z předaných znaků. Porovnává poslední znak řetězce se všemi znaky v anyOf, poté porovnává předchozí a tak dále. Vrací index první nalezené shody.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)<char_t>& | [Array](../../array/) znaků k vyhledání. Pořadí není důležité. |

### Návratová hodnota

[Index](../../index/) posledního odpovídajícího znaku nebo -1, pokud nebyl nalezen.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

Prohledává podřetězec zpětně a hledá některý z předaných znaků. Porovnává poslední znak řetězce se všemi znaky v anyOf, poté porovnává předchozí a tak dále. Vrací index první nalezené shody.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)<char_t>& | [Array](../../array/) znaků k vyhledání. Pořadí není důležité. |
| startindex | **int32_t** | [Index](../../index/) pro zahájení vyhledávání. |

### Návratová hodnota

[Index](../../index/) posledního odpovídajícího znaku nebo -1, pokud nebyl nalezen.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

Prohledává podřetězec zpětně a hledá některý z předaných znaků. Porovnává poslední znak řetězce se všemi znaky v anyOf, poté porovnává předchozí a tak dále. Vrací index první nalezené shody.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)<char_t>& | [Array](../../array/) znaků k vyhledání. Pořadí není důležité. |
| startindex | **int32_t** | [Index](../../index/) pro zahájení vyhledávání. |
| count | **int32_t** | Počet znaků, které mají být prohledány. |

### Návratová hodnota

[Index](../../index/) posledního odpovídajícího znaku nebo -1, pokud nebyl nalezen.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
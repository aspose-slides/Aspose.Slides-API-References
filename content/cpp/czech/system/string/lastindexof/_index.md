---
title: LastIndexOf()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vyhledávání podřetězce pozpátku.
type: docs
weight: 651
url: /cs/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method


Vyhledávání podřetězce pozpátku.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, kde začít vyhledávat. |

### Návratová hodnota

[Index](../../index/) posledního nalezeného podřetězce nebo -1, pokud nebyl nalezen. Pro prázdný vyhledávací řetězec vždy vrací délku řetězce.

## String::LastIndexOf(const String\&, System::StringComparison) const method


Vyhledávání podřetězce pozpátku.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

[Index](../../index/) posledního nalezeného podřetězce nebo -1, pokud nebyl nalezen. Pro prázdný vyhledávací řetězec vždy vrací délku řetězce.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Vyhledávání podřetězce pozpátku.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, kde začít vyhledávat. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

[Index](../../index/) posledního nalezeného podřetězce nebo -1, pokud nebyl nalezen. Pro prázdný vyhledávací řetězec vždy vrací délku řetězce.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Vyhledávání podřetězce pozpátku.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, kde začít vyhledávat. |
| count | int | Počet znaků, které se mají prohledat. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

[Index](../../index/) posledního nalezeného podřetězce nebo -1, pokud nebyl nalezen. Pro prázdný vyhledávací řetězec vždy vrací startIndex+count.

## String::LastIndexOf(char_t) const method


Vyhledávání znaku pozpátku.

```cpp
int System::String::LastIndexOf(char_t value) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Znak, který se má vyhledat. |

### Návratová hodnota

[Index](../../index/) poslední pozice znaku nebo -1, pokud nebyl nalezen.

## String::LastIndexOf(char_t, int32_t) const method


Vyhledávání znaku pozpátku.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Znak, který se má vyhledat. |
| startIndex | **int32_t** | [Index](../../index/) pro zahájení vyhledávání. |

### Návratová hodnota

[Index](../../index/) poslední pozice znaku od startIndex nebo -1, pokud nebyl nalezen.

## String::LastIndexOf(char_t, int32_t, int32_t) const method


Vyhledávání znaku pozpátku.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char_t | Znak, který se má vyhledat. |
| startIndex | **int32_t** | [Index](../../index/) pro zahájení vyhledávání. |
| count | **int32_t** | Počet znaků, které se mají prohledat |

### Návratová hodnota

[Index](../../index/) poslední pozice znaku od startIndex nebo -1, pokud nebyl nalezen.

## Viz také

* Výčet [StringComparison](../../stringcomparison/)
* Třída [String](../)
* Prostor názvů [System](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: IndexOf()
second_title: Aspose.Slides pro C++ referenci API
description: Vyhledávání podřetězce vpřed.
type: docs
weight: 625
url: /cs/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const method

Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

[Index](../../index/) první nalezené podřetězce nebo -1, pokud nebyl nalezen. Pro prázdný řetězec vyhledávání vždy vrací 0.

## String::IndexOf(char_t, int) const method

Character forward lookup.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak, který se má vyhledat. |
| startIndex | int | [Index](../../index/) pro zahájení vyhledávání. |

### Návratová hodnota

[Index](../../index/) první pozice znaku od startIndex nebo -1, pokud nebyl nalezen.

## String::IndexOf(char_t, int, int) const method

Character forward lookup in substring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Znak, který se má vyhledat. |
| startIndex | int | [Index](../../index/) pro zahájení vyhledávání. |
| count | int | Počet znaků, které se mají prohledat. |

### Návratová hodnota

[Index](../../index/) první pozice znaku od startIndex nebo -1, pokud nebyl nalezen.

## String::IndexOf(const String\&, int) const method

Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, od které začít vyhledávat. |

### Návratová hodnota

[Index](../../index/) první nalezený podřetězec nebo -1, pokud nebyl nalezen. Pro prázdný řetězec vyhledávání vždy vrací startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const method

Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, od které začít vyhledávat. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

[Index](../../index/) první nalezený podřetězec nebo -1, pokud nebyl nalezen. Pro prázdný řetězec vyhledávání vždy vrací startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const method

Substring forward lookup.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, od které začít vyhledávat. |
| count | int | počet znaků, které se mají prohledat. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

[Index](../../index/) první nalezený podřetězec nebo -1, pokud nebyl nalezen. Pro prázdný řetězec vyhledávání vždy vrací startIndex.

## String::IndexOf(const String\&, int, int) const method

Substring forward lookup.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | Podřetězec, který se má vyhledat. |
| startIndex | int | Pozice ve zdrojovém řetězci, od které začít vyhledávat. |
| count | int | počet znaků, které se mají prohledat. |

### Návratová hodnota

[Index](../../index/) první nalezený podřetězec nebo -1, pokud nebyl nalezen. Pro prázdný řetězec vyhledávání vždy vrací startIndex.

## Viz také

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
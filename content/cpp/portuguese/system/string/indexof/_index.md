---
title: IndexOf()
second_title: Aspose.Slides para C++ Referência da API
description: Busca progressiva de substring.
type: docs
weight: 625
url: /pt/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const método

Busca progressiva de substring.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

[Index](../../index/) do primeiro substring encontrado ou -1 se não encontrado. Para string de busca vazia, sempre retorna 0.

## String::IndexOf(char_t, int) const método

Busca progressiva de caractere.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c | char_t | Caractere a ser procurado. |
| startIndex | int | [Index](../../index/) para iniciar a busca em. |

### Valor de Retorno

[Index](../../index/) da primeira posição de caractere a partir de startIndex ou -1 se não encontrado.

## String::IndexOf(char_t, int, int) const método

Busca progressiva de caractere em substring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c | char_t | Caractere a ser procurado. |
| startIndex | int | [Index](../../index/) para iniciar a busca em. |
| count | int | Número de caracteres a percorrer. |

### Valor de Retorno

[Index](../../index/) da primeira posição de caractere a partir de startIndex ou -1 se não encontrado.

## String::IndexOf(const String\&, int) const método

Busca progressiva de substring.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem para iniciar a busca. |

### Valor de Retorno

[Index](../../index/) do primeiro substring encontrado ou -1 se não encontrado. Para string de busca vazia, sempre retorna startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const método

Busca progressiva de substring.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem para iniciar a busca. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

[Index](../../index/) do primeiro substring encontrado ou -1 se não encontrado. Para string de busca vazia, sempre retorna startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const método

Busca progressiva de substring.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem para iniciar a busca. |
| count | int | número de caracteres a percorrer. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

[Index](../../index/) do primeiro substring encontrado ou -1 se não encontrado. Para string de busca vazia, sempre retorna startIndex.

## String::IndexOf(const String\&, int, int) const método

Busca progressiva de substring.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem para iniciar a busca. |
| count | int | número de caracteres a percorrer. |

### Valor de Retorno

[Index](../../index/) do primeiro substring encontrado ou -1 se não encontrado. Para string de busca vazia, sempre retorna startIndex.

## Veja Também

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
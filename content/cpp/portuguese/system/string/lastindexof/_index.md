---
title: LastIndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Busca regressiva de substring.
type: docs
weight: 651
url: /pt/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const método

Busca regressiva de substring.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem onde iniciar a busca. |

### Valor de Retorno

[Index](../../index/) da última substring encontrada ou -1 se não encontrada. Para string de busca vazia, sempre retorna o comprimento da string.

## String::LastIndexOf(const String\&, System::StringComparison) const método

Busca regressiva de substring.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

[Index](../../index/) da última substring encontrada ou -1 se não encontrada. Para string de busca vazia, sempre retorna o comprimento da string.

## String::LastIndexOf(const String\&, int, System::StringComparison) const método

Busca regressiva de substring.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem onde iniciar a busca. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

[Index](../../index/) da última substring encontrada ou -1 se não encontrada. Para string de busca vazia, sempre retorna o comprimento da string.

## String::LastIndexOf(const String\&, int, int, StringComparison) const método

Busca regressiva de substring.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | Substring a ser procurada. |
| startIndex | int | Posição na string de origem onde iniciar a busca. |
| count | int | Número de caracteres a percorrer. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

[Index](../../index/) da última substring encontrada ou -1 se não encontrada. Para string de busca vazia, sempre retorna startIndex+count.

## String::LastIndexOf(char_t) const método

Busca regressiva de caractere.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | Caractere a ser procurado. |

### Valor de Retorno

[Index](../../index/) da última posição de caractere ou -1 se não encontrado.

## String::LastIndexOf(char_t, int32_t) const método

Busca regressiva de caractere.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | Caractere a ser procurado. |
| startIndex | **int32_t** | [Index](../../index/) para iniciar a busca em. |

### Valor de Retorno

[Index](../../index/) da última posição de caractere desde startIndex ou -1 se não encontrado.

## String::LastIndexOf(char_t, int32_t, int32_t) const método

Busca regressiva de caractere.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | Caractere a ser procurado. |
| startIndex | **int32_t** | [Index](../../index/) para iniciar a busca em. |
| count | **int32_t** | Número de caracteres a percorrer. |

### Valor de Retorno

[Index](../../index/) da última posição de caractere desde startIndex ou -1 se não encontrado.

## Ver Também

* Enum [StringComparison](../../stringcomparison/)
* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)
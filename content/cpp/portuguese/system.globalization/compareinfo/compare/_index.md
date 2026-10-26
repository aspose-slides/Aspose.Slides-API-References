---
title: Compare()
second_title: Referência da API Aspose.Slides para C++
description: Compara strings. Não implementado.
type: docs
weight: 66
url: /pt/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const method

Compara strings. Não implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | String LHS. |
| string2 | const [String](../../../system/string/)\& | String RHS. |

### Valor de Retorno

Valor negativo se a string LHS precede a string RHS, zero se elas coincidem, valor positivo caso contrário.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const method

Compara strings. Apenas os modos Ordinal e OrdinalIgnoreCase são suportados.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | String LHS. |
| b | const [String](../../../system/string/)\& | String RHS. |
| options | [CompareOptions](../../compareoptions/) | Tipo de comparação [String](../../../system/string/). |

### Valor de Retorno

Valor negativo se a string LHS precede a string RHS, zero se elas coincidem, valor positivo caso contrário.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const method

Compara uma seção de uma string com uma seção de outra string. Não implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primeira string. |
| offset1 | int | Índice inicial dos caracteres em **string1**. |
| length1 | int | Número de caracteres em **string1** a serem comparados. |
| string2 | const [String](../../../system/string/)\& | Segunda string. |
| offset2 | int | Índice inicial dos caracteres em **string2**. |
| length2 | int | Número de caracteres em **string2** a serem comparados. |

### Valor de Retorno

Valor negativo se a seção da primeira string preceder a seção da segunda string, zero se elas coincidirem, valor positivo caso contrário.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const method

Compara a seção final de uma string com a seção final de outra string usando métodos de comparação de strings. Não implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primeira string. |
| offset1 | int | Índice inicial dos caracteres em **string1**. |
| string2 | const [String](../../../system/string/)\& | Segunda string. |
| offset2 | int | Índice inicial dos caracteres em **string2**. |
| options | [CompareOptions](../../compareoptions/) | Opções de comparação [String](../../../system/string/). |

### Valor de Retorno

Valor negativo se a seção da primeira string preceder a seção da segunda string, zero se elas coincidirem, valor positivo caso contrário.

## CompareInfo::Compare(const String\&, int, const String\&, int) const method

Compara a seção final de uma string com a seção final de outra string. Não implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primeira string. |
| offset1 | int | Índice inicial dos caracteres em **string1**. |
| string2 | const [String](../../../system/string/)\& | Segunda string. |
| offset2 | int | Índice inicial dos caracteres em **string2**. |

### Valor de Retorno

Valor negativo se a seção da primeira string preceder a seção da segunda string, zero se elas coincidirem, valor positivo caso contrário.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const method

Compara uma seção de uma string com uma seção de outra string usando métodos de comparação de strings. Não implementado.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Primeira string. |
| offset1 | int | Índice inicial dos caracteres em **string1**. |
| length1 | int | Número de caracteres em **string1** a serem comparados. |
| string2 | const [String](../../../system/string/)\& | Segunda string. |
| offset2 | int | Índice inicial dos caracteres em **string2**. |
| length2 | int | Número de caracteres em **string2** a serem comparados. |
| options | [CompareOptions](../../compareoptions/) | Opções de comparação [String](../../../system/string/). |

### Valor de Retorno

Valor negativo se a seção da primeira string preceder a seção da segunda string, zero se elas coincidirem, valor positivo caso contrário.

## Veja Também

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)
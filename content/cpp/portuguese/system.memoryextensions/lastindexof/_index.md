---
title: LastIndexOf()
second_title: Aspose.Slides para C++ Referência da API
description: Encontra a última ocorrência de uma sequência dentro de um span.
type: docs
weight: 209
url: /pt/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Encontra a última ocorrência de uma sequência dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A sequência a ser procurada |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) função


Encontra a última ocorrência de um único valor dentro de um span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde buscar |
| value | const T\& | O valor a ser procurado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Encontra a última ocorrência de uma sequência dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A sequência a ser procurada |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) função


Encontra a última ocorrência de um único valor dentro de um span mutável.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde buscar |
| value | const T\& | O valor a ser procurado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) função


Encontra a última ocorrência de um valor dentro de um span usando a comparação de strings especificada.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span onde buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O valor a ser procurado |
| comparisonType | [StringComparison](../../system/stringcomparison/) | O tipo de comparação de strings a ser executado |

### Valor de retorno

O índice baseado em zero da última ocorrência, ou -1 se não encontrado

## Veja também

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
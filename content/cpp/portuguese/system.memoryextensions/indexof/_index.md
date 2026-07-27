---
title: IndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Encontra o índice de um valor ReadOnlySpan<T> em outro ReadOnlySpan<T>
type: docs
weight: 144
url: /pt/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Encontra o índice de um valor ReadOnlySpan\<T\> em outro ReadOnlySpan\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span onde será feita a pesquisa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span a ser pesquisada |

### Valor de retorno

O índice baseado em zero da primeira ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) function


Encontra o índice de um único valor em um ReadOnlySpan\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos na span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span onde será feita a pesquisa |
| value | const T\& | O valor a ser pesquisado |

### Valor de retorno

O índice baseado em zero da primeira ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Encontra o índice de um valor ReadOnlySpan\<T\> em um Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A span onde será feita a pesquisa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span a ser pesquisada |

### Valor de retorno

O índice baseado em zero da primeira ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) function


Encontra o índice de um único valor em um Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos na span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A span onde será feita a pesquisa |
| value | const T\& | O valor a ser pesquisado |

### Valor de retorno

O índice baseado em zero da primeira ocorrência, ou -1 se não encontrado

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Encontra o índice de um valor ReadOnlySpan\<char16_t\> em um ReadOnlySpan\<char16_t\> com StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A span onde será feita a pesquisa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O valor a ser pesquisado |
| comparisonType | [StringComparison](../../system/stringcomparison/) | O tipo de comparação de string a ser usado |

### Valor de retorno

O índice baseado em zero da primeira ocorrência, ou -1 se não encontrado

## Veja também

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
---
title: Overlaps()
second_title: Referência da API Aspose.Slides para C++
description: Determina se dois ReadOnlySpans se sobrepõem na memória sem calcular o deslocamento.
type: docs
weight: 274
url: /pt/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Determina se dois ReadOnlySpans se sobrepõem na memória sem calcular o deslocamento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O primeiro span a ser verificado para sobreposição |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O segundo span a ser verificado para sobreposição |

### Valor de retorno

true se as spans compartilham quaisquer locais de memória comuns, false caso contrário

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Determina se um [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) se sobrepõem na memória sem calcular o deslocamento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O [Span](../../system/span/) a ser verificado para sobreposição |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O [ReadOnlySpan](../../system/readonlyspan/) a ser verificado para sobreposição |

### Valor de retorno

true se as spans compartilham quaisquer locais de memória comuns, false caso contrário

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) função


Determina se dois ReadOnlySpans se sobrepõem na memória e calculam o deslocamento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O primeiro span a ser verificado para sobreposição |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O segundo span a ser verificado para sobreposição |
| elementOffset | **int32_t**\& | Parâmetro de saída que recebe o deslocamento entre as spans se elas se sobreporem |

### Valor de retorno

true se as spans compartilham quaisquer locais de memória comuns, false caso contrário

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) função


Determina se um [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) se sobrepõem na memória e calculam o deslocamento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O [Span](../../system/span/) a ser verificado para sobreposição |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O [ReadOnlySpan](../../system/readonlyspan/) a ser verificado para sobreposição |
| elementOffset | **int32_t**\& | Parâmetro de saída que recebe o deslocamento entre as spans se elas se sobreporem |

### Valor de retorno

true se as spans compartilham quaisquer locais de memória comuns, false caso contrário

## Ver também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)
---
title: Count()
second_title: Aspose.Slides para C++ Referência da API
description: Conta ocorrências de um valor em um span somente leitura.
type: docs
weight: 118
url: /pt/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) function


Conta ocorrências de um valor em um span somente leitura.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| value | const T\& | O valor a contar |

### Valor de retorno

O número de vezes que o valor aparece no span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Conta ocorrências de um span dentro de outro span somente leitura.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span cujas ocorrências devem ser contadas |

### Valor de retorno

O número de vezes que o valor aparece no span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) function


Conta ocorrências de um único valor em um Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde pesquisar |
| value | const T\& | O valor cujas ocorrências devem ser contadas |

### Valor de retorno

O número de ocorrências do valor no span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Conta ocorrências de um ReadOnlySpan<T> em um Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span onde pesquisar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span contendo os valores cujas ocorrências devem ser contadas |

### Valor de retorno

O número de ocorrências do span de valores no span alvo

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)
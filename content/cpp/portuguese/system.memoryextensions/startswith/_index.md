---
title: StartsWith()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se o span começa com o valor especificado.
type: docs
weight: 352
url: /pt/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) função

Verifica se o span começa com o valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado |
| value | const T\& | O valor a ser verificado no início do span |

### Valor de retorno

true se o span começa com o valor, false caso contrário

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Verifica se o span começa com o span de valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span contendo os valores a serem verificados no início |

### Valor de retorno

true se o span começa com o span de valor, false caso contrário

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Verifica se o span mutável começa com o span de valor somente leitura especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável a ser verificado |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span somente leitura contendo os valores a serem verificados |

### Valor de retorno

true se o span começa com o span de valor, false caso contrário

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) função


Verifica se o span somente leitura começa com o span de valor mutável especificado.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span somente leitura a ser verificado |
| value | const [Span](../../system/span/)\<T\>\& | O span mutável contendo os valores a serem verificados |

### Valor de retorno

true se o span começa com o span de valor, false caso contrário

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) função


Verifica se o span de caracteres começa com o span de valor especificado usando comparação de strings.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres a ser verificado |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span de caracteres contendo os valores a serem verificados |
| comparisonType | [StringComparison](../../system/stringcomparison/) | O tipo de comparação de strings a ser realizada |

### Valor de retorno

true se o span começa com o span de valor, false caso contrário

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) função


Verifica se um span de strings começa com o array de caracteres especificado.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | O span de strings a ser verificado |
| val | const char16_t * | O array de caracteres a ser verificado no início |

### Valor de retorno

true se o span começa com o array de caracteres, false caso contrário

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* classe [ReadOnlySpan](../../system/readonlyspan/)
* classe [Span](../../system/span/)
* classe [String](../../system/string/)
* namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
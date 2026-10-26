---
title: EndsWith()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se um ReadOnlySpan<T> termina com um único valor.
type: docs
weight: 131
url: /pt/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) função


Determina se um ReadOnlySpan<T> termina com um único valor.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado |
| value | const T\& | O valor a ser verificado no final do span |

### Valor de retorno

true se o span termina com o valor, false caso contrário

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função


Determina se um ReadOnlySpan<T> termina com outro ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado no final do span de destino |

### Valor de retorno

true se o span termina com o span de valor, false caso contrário

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função


Determina se um Span<T> termina com um ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span a ser verificado |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado no final do span de destino |

### Valor de retorno

true se o span termina com o span de valor, false caso contrário

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) função


Determina se um ReadOnlySpan<T> termina com um Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span a ser verificado |
| value | const [Span](../../system/span/)\<T\>\& | O span a ser verificado no final do span de destino |

### Valor de retorno

true se o span termina com o span de valor, false caso contrário

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) função


Determina se um Span<T> termina com outro Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nas spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span a ser verificado |
| value | const [Span](../../system/span/)\<T\>\& | O span a ser verificado no final do span de destino |

### Valor de retorno

true se o span termina com o span de valor, false caso contrário

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) função


Determina se um ReadOnlySpan<char16_t> termina com o valor especificado usando StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span a ser verificado |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O valor a ser verificado no final do span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | O tipo de comparação de string a ser usado |

### Valor de retorno

true se o span termina com o valor, false caso contrário

## Veja também

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
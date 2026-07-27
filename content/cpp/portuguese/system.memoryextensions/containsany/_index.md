---
title: ContainsAny()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se um span somente leitura contém algum dos dois valores.
type: docs
weight: 53
url: /pt/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Verifica se um **span** somente leitura contém algum dos dois valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde procurar |
| value0 | const T\& | O primeiro valor a ser procurado |
| value1 | const T\& | O segundo valor a ser procurado |

### Valor de retorno

true se algum dos valores for encontrado no span, false caso contrário

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Verifica se um **span** somente leitura contém algum dos três valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde procurar |
| value0 | const T\& | O primeiro valor a ser procurado |
| value1 | const T\& | O segundo valor a ser procurado |
| value2 | const T\& | O terceiro valor a ser procurado |

### Valor de retorno

true se algum dos valores for encontrado no span, false caso contrário

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function

Verifica se um **span** mutável contém algum dos dois valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde procurar |
| value0 | const T\& | O primeiro valor a ser procurado |
| value1 | const T\& | O segundo valor a ser procurado |

### Valor de retorno

true se algum dos valores for encontrado no span, false caso contrário

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Verifica se um **span** mutável contém algum dos três valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde procurar |
| value0 | const T\& | O primeiro valor a ser procurado |
| value1 | const T\& | O segundo valor a ser procurado |
| value2 | const T\& | O terceiro valor a ser procurado |

### Valor de retorno

true se algum dos valores for encontrado no span, false caso contrário

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Verifica se um **span** somente leitura contém algum valor de outro span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde procurar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span de valores a ser procurado |

### Valor de retorno

true se algum valor de **values** for encontrado no span, false caso contrário

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Verifica se um **span** mutável contém algum valor de um **span** somente leitura.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde procurar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O **span** somente leitura de valores a ser procurado |

### Valor de retorno

true se algum valor de **values** for encontrado no span, false caso contrário

## Veja também

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)
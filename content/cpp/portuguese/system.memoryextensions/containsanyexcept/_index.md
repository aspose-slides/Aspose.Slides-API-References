---
title: ContainsAnyExcept()
second_title: Aspose.Slides para C++ - Referência da API
description: Verifica se um span somente leitura contém algum elemento, exceto três valores especificados.
type: docs
weight: 66
url: /pt/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) função

Verifica se um span somente leitura contém algum elemento, exceto três valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| value0 | const T\& | O primeiro valor a excluir |
| value1 | const T\& | O segundo valor a excluir |
| value2 | const T\& | O terceiro valor a excluir |

### Valor de retorno

true se algum elemento diferente dos valores especificados for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) função

Verifica se um span mutável contém algum elemento, exceto três valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde pesquisar |
| value0 | const T\& | O primeiro valor a excluir |
| value1 | const T\& | O segundo valor a excluir |
| value2 | const T\& | O terceiro valor a excluir |

### Valor de retorno

true se algum elemento diferente dos valores especificados for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) função

Verifica se um span somente leitura contém algum elemento, exceto dois valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| value0 | const T\& | O primeiro valor a excluir |
| value1 | const T\& | O segundo valor a excluir |

### Valor de retorno

true se algum elemento diferente dos valores especificados for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) função

Verifica se um span mutável contém algum elemento, exceto dois valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde pesquisar |
| value0 | const T\& | O primeiro valor a excluir |
| value1 | const T\& | O segundo valor a excluir |

### Valor de retorno

true se algum elemento diferente dos valores especificados for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) função

Verifica se um span somente leitura contém algum elemento, exceto um valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| value | const T\& | O valor a excluir |

### Valor de retorno

true se algum elemento diferente do valor especificado for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) função

Verifica se um span mutável contém algum elemento, exceto um valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde pesquisar |
| value | const T\& | O valor a excluir |

### Valor de retorno

true se algum elemento diferente do valor especificado for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) função

Verifica se um span somente leitura contém algum elemento, exceto aqueles em outro span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde pesquisar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span de valores a excluir |

### Valor de retorno

true se algum elemento não presente em values for encontrado, false caso contrário

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) função

Verifica se um span mutável contém algum elemento, exceto aqueles em um span somente leitura.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos nos spans |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde pesquisar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span somente leitura de valores a excluir |

### Valor de retorno

true se algum elemento não presente em values for encontrado, false caso contrário

## Veja Também

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
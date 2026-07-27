---
title: AsSpan()
second_title: Referência da API Aspose.Slides para C++
description: Cria um span a partir de um array.
type: docs
weight: 1
url: /pt/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) função

Cria um span a partir de um array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no array. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | O array de origem. |
| start | **int32_t** | O índice inicial no array. |
| length | **int32_t** | O comprimento do span. |

### Valor de retorno

Span<T> que abrange a porção especificada do array.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) função

Cria um span somente leitura a partir de uma string.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | A string de origem. |
| start | **int32_t** | O índice inicial na string. |
| length | **int32_t** | O comprimento do span. |

### Valor de retorno

ReadOnlySpan<char16_t> que abrange a porção especificada da string.

## Ver também

* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [Span](../../system/span/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)
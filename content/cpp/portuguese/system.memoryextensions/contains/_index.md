---
title: Contains()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se um span somente leitura contém um valor específico.
type: docs
weight: 40
url: /pt/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) function

Verifica se um span somente leitura contém um valor específico.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | O span onde procurar |
| value | const T\& | O valor a ser procurado |

### Valor de retorno

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) function

Verifica se um span mutável contém um valor específico.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de elementos no span |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | O span mutável onde procurar |
| value | const T\& | O valor a ser procurado |

### Valor de retorno

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Verifica se um span de caracteres contém outro span de caracteres com regras de comparação especificadas.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span onde procurar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O span a ser procurado |
| comparisonType | [StringComparison](../../system/stringcomparison/) | O tipo de comparação de string a ser realizado |

### Valor de retorno

true if value is found in span, false otherwise

## Veja também

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Espaço de nomes [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)
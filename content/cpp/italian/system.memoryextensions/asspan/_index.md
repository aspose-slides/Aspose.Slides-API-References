---
title: AsSpan()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea uno span da un array.
type: docs
weight: 1
url: /it/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) funzione

Crea uno span da un array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nell'array. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | L'array di origine. |
| start | **int32_t** | L'indice iniziale nell'array. |
| length | **int32_t** | La lunghezza dello span. |

### Valore restituito

Span<T> che copre la porzione specificata dell'array.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) funzione

Crea uno span di sola lettura da una stringa.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | La stringa di origine. |
| start | **int32_t** | L'indice iniziale nella stringa. |
| length | **int32_t** | La lunghezza dello span. |

### Valore restituito

ReadOnlySpan<char16_t> che copre la porzione specificata della stringa.

## Vedi anche

* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [Span](../../system/span/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)
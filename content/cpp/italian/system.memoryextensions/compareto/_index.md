---
title: CompareTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta due intervalli di caratteri secondo le regole di confronto delle stringhe specificate.
type: docs
weight: 404
url: /it/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Confronta due intervalli di caratteri secondo le regole di confronto delle stringhe specificate.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Il primo intervallo di caratteri |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Il secondo intervallo di caratteri |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Il tipo di confronto delle stringhe da eseguire |

### Valore di ritorno

Valore negativo se span < other, zero se uguale, valore positivo se span > other

## Vedi anche

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)
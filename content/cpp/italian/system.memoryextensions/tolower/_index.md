---
title: ToLower()
second_title: Riferimento API Aspose.Slides per C++
description: Converte i caratteri in minuscolo usando la cultura specificata.
type: docs
weight: 443
url: /it/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funzione

Converte i caratteri in minuscolo usando la cultura specificata.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | L'intervallo di caratteri di origine da convertire |
| destination | [Span](../../system/span/)\<char16_t\>\& | L'intervallo di destinazione per memorizzare i caratteri convertiti |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | La cultura da usare per la conversione (nullptr per la cultura corrente) |

### Valore restituito

Numero di caratteri convertiti, o -1 se la destinazione è troppo piccola

## Vedi anche

* Definizione di tipo [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Classe [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)
---
title: ToUpper()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte i caratteri in maiuscolo usando la cultura specificata.
type: docs
weight: 469
url: /it/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funzione

Converte i caratteri in maiuscolo usando la cultura specificata.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | L'intervallo di caratteri sorgente da convertire |
| destination | [Span](../../system/span/)\<char16_t\>\& | L'intervallo di destinazione dove memorizzare i caratteri convertiti |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | La cultura da usare per la conversione (nullptr per la cultura corrente) |

### Valore di ritorno

Numero di caratteri convertiti, o -1 se la destinazione è troppo piccola

## Vedi anche

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Classe [CultureInfo](../../system.globalization/cultureinfo/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)
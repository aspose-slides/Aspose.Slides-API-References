---
title: CompressionLevel
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica i livelli di compressione ZIP per i file OpenXML. I livelli più alti forniscono una compressione migliore al costo di una elaborazione più lenta.
type: docs
weight: 846
url: /it/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Specifica i livelli di compressione ZIP per i file OpenXML. I livelli più alti forniscono una compressione migliore al costo di una elaborazione più lenta.

```cpp
enum class CompressionLevel
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Nessuna compressione viene applicata. I file sono archiviati così come sono. |
| Level1 | 1 | Compressione più veloce con il rapporto di compressione più basso. |
| Level2 | 2 | Compressione più veloce con un rapporto di compressione leggermente migliore rispetto a [CompressionLevel::Level1](./). |
| Level3 | 3 | Fornisce una compressione migliore rispetto a [CompressionLevel::Level2](./) con un impatto sulle prestazioni moderato. |
| Level4 | 4 | Fornisce una compressione migliore rispetto a [CompressionLevel::Level3](./). |
| Level5 | 5 | Fornisce una compressione migliorata rispetto a [CompressionLevel::Level4](./) con un tempo di elaborazione aggiuntivo. |
| Level6 | 6 | Compressione standard, che offre un buon equilibrio tra velocità di compressione e dimensione del file. Il livello di compressione predefinito. |
| Level7 | 7 | Fornisce una compressione più alta rispetto a [CompressionLevel::Level6](./) con un'elaborazione più lenta. |
| Level8 | 8 | Fornisce una compressione più alta rispetto a [CompressionLevel::Level7](./). |
| Level9 | 9 | Compressione massima. Produce la dimensione di file più piccola con la velocità di elaborazione più lenta. |

## Vedi anche

* Namespace [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)
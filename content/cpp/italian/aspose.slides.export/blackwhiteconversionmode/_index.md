---
title: BlackWhiteConversionMode
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce opzioni che controllano come le immagini delle diapositive verranno convertite in immagini bitonali.
type: docs
weight: 820
url: /it/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Fornisce opzioni che controllano come le immagini delle diapositive verranno convertite in immagini bitonali.

```cpp
enum class BlackWhiteConversionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | 0 | Specifica nessun algoritmo di conversione. Verrà utilizzato l'algoritmo implementato nel codec TIFF. (Default) |
| Dithering | 1 | Specifica l'algoritmo di dithering (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Specifica l'algoritmo di dithering Floyd-Steinberg. |
| Auto | 3 | Specifica l'algoritmo di soglia calcolato automaticamente (Otsu). |
| AutoOtsu | 4 | Specifica l'algoritmo di soglia di Otsu calcolato automaticamente. |
| Threshold25 | 5 | Specifica l'algoritmo di soglia statico (25%). |
| Threshold50 | 6 | Specifica l'algoritmo di soglia statico (50%). |
| Threshold75 | 7 | Specifica l'algoritmo di soglia statico (75%). |

## Vedi anche

* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)
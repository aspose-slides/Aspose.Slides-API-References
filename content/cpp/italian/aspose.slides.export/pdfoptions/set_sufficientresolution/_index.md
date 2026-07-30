---
title: set_SufficientResolution()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF.
type: docs
weight: 365
url: /it/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) method

Imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Osservazioni

La proprietà influisce sulle dimensioni del file, sul tempo di esportazione e sulla qualità dell'immagine.

Il valore predefinito è **96**.

L'effetto di questo parametro dipende da diversi fattori. L'algoritmo cerca di ottenere la migliore dimensione dell'immagine di output in base al valore della proprietà, alle dimensioni dell'immagine di origine e alle dimensioni del riquadro dell'immagine. L'utilizzo di valori di proprietà simili può dare lo stesso risultato. Si consiglia di usare passo 16 o 32 per ottenere un effetto visibile.

Scrivi **float**. 
## Vedi anche

* Classe [PdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
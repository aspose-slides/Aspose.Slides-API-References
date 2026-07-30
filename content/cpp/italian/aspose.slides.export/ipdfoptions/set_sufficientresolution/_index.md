---
title: set_SufficientResolution()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF.
type: docs
weight: 326
url: /it/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) method

Imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## Osservazioni

La proprietà influisce sulla dimensione del file, sul tempo di esportazione e sulla qualità dell'immagine.

Il valore predefinito è **96**.

L'effetto di questo parametro dipende da alcuni fattori. L'algoritmo cerca di ottenere la dimensione migliore dell'immagine in output in base al valore della proprietà, alle dimensioni dell'immagine di origine e alle dimensioni del frame dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si consiglia di utilizzare step 16 o 32 per ottenere un effetto visibile.

Scrivi **float**. 
## Vedi anche

* Classe [IPdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
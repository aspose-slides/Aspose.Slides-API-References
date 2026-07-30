---
title: get_SufficientResolution()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che determina la risoluzione delle immagini all'interno del documento PDF.
type: docs
weight: 313
url: /it/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() metodo

Restituisce un valore che determina la risoluzione delle immagini all'interno del documento PDF.

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## Osservazioni

La proprietà influisce sulla dimensione del file, sul tempo di esportazione e sulla qualità dell'immagine.

Il valore predefinito è **96**.

L'effetto di questo parametro dipende da pochi fattori. L'algoritmo cerca di ottenere la migliore dimensione dell'immagine in output in base al valore della proprietà, alla dimensione dell'immagine di origine e alla dimensione del riquadro dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si consiglia di usare un passo di 16 o 32 per ottenere un effetto visibile.

Leggi **float**. 

## Vedi anche

* Classe [IPdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)
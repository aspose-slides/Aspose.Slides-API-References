---
title: get_SufficientResolution()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce un valore che determina la risoluzione delle immagini all'interno del documento PDF.
type: docs
weight: 352
url: /it/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() metodo

Restituisce un valore che determina la risoluzione delle immagini all'interno del documento PDF.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Osservazioni

La proprietà influisce sulla dimensione del file, sul tempo di esportazione e sulla qualità dell'immagine.

Il valore predefinito è **96**.

L'effetto di questo parametro dipende da pochi fattori. L'algoritmo tenta di ottenere la migliore dimensione dell'immagine di output in base al valore della proprietà, alla dimensione dell'immagine sorgente e alla dimensione del frame dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si consiglia di utilizzare passi di 16 o 32 per ottenere un effetto visibile.

Lettura **float**.

## Vedi anche

* Classe [PdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
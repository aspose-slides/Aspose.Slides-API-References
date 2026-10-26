---
title: jpeg_quality property
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality proprietà
Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF.
            Lettura/scrittura **int**.


### Osservazioni

Ha effetto solo quando un documento contiene immagini JPEG.


Utilizza questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento quando lo si salva in formato PDF.
            Il valore può variare da 0 a 100 dove 0 significa la qualità più bassa ma la massima compressione e 100 significa la migliore qualità ma la minima compressione.


Il valore predefinito è **100** .

### Definizione:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Vedi anche
* classe [`PdfOptions`](/slides/python-net/it/aspose.slides.export/pdfoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
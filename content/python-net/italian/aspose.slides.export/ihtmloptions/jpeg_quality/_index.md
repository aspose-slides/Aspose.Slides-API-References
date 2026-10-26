---
title: jpeg_quality property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## proprietà jpeg_quality
Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF.
            Lettura/scrittura **int**.


### Osservazioni

Ha effetto solo quando un documento contiene immagini JPEG.


Usa questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento quando lo si salva in formato PDF.
            Il valore può variare da 0 a 100, dove 0 indica la qualità più bassa ma la massima compressione e 100 indica la migliore qualità ma la compressione minima.


Il valore predefinito è **95** .

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
* classe [`IHtmlOptions`](/slides/python-net/it/aspose.slides.export/ihtmloptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
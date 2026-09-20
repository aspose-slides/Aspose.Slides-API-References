---
title: best_images_compression_ratio property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio proprietà
Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata 
automaticamente. Se impostata su **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. 
La selezione del miglior rapporto di compressione delle immagini è computazionalmente costosa e richiede 
una quantità aggiuntiva di RAM, e questa opzione è **bool**.false per impostazione predefinita.


### Osservazioni

Il valore predefinito è **bool**.false.

### Definizione:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### Vedi anche
* classe [`PdfOptions`](/slides/python-net/it/aspose.slides.export/pdfoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
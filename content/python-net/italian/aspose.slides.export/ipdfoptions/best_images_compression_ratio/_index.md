---
title: best_images_compression_ratio property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio proprietà
Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostata su **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione minore del documento PDF risultante. La selezione del miglior rapporto di compressione dell'immagine è computazionalmente costosa e richiede una quantità aggiuntiva di RAM, e questa opzione è **bool**.false per impostazione predefinita.


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
* classe [`IPdfOptions`](/slides/python-net/it/aspose.slides.export/ipdfoptions)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
---
title: write_shape_start method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Chiamato prima del rendering di shape. Chiamato una volta per ciascun shape. Se questa funzione scrive qualcosa su generator, la generazione dell’immagine della diapositiva corrente sarà terminata, il frammento html aggiunto inserito e una nuova immagine verrà avviata sopra la precedente.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator) | Oggetto di output. |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Shape che sta per essere renderizzato. |



### Vedi anche
* classe [`IHtmlFormattingController`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
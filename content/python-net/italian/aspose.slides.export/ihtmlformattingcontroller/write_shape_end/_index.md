---
title: write_shape_end method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Chiamata prima del rendering della forma. Chiamata una volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento HTML aggiunto inserito e una nuova immagine sarà avviata sopra la precedente.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator) | Oggetto di output. |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Forma che viene renderizzata per ultima. |



### Vedi anche
* classe [`IHtmlFormattingController`](/slides/python-net/it/aspose.slides.export/ihtmlformattingcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
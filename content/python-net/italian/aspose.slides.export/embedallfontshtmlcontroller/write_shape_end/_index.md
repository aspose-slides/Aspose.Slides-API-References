---
title: write_shape_end method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Chiamato prima del rendering di shape. Chiamato una volta per ciascuna shape. Se questa funzione scrive qualcosa su generator, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator) | Oggetto di output. |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Shape che è renderizzata per ultima. |


### Vedi anche
* classe [`EmbedAllFontsHtmlController`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
---
title: write_shape_start method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Chiamata prima del rendering della shape. Chiamata una volta per ciascuna shape. Se questa funzione scrive qualcosa sul generator, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator) | Oggetto di output. |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Shape che sta per essere renderizzata. |

### Vedi anche
* classe [`EmbedAllFontsHtmlController`](/slides/python-net/it/aspose.slides.export/embedallfontshtmlcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/it/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
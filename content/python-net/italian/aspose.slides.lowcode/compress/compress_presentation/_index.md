---
title: compress_presentation method
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Riduce le dimensioni di una presentazione applicando tutti i passaggi di compressione disponibili:
            
* Rimuove le diapositive master inutilizzate **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Rimuove le diapositive layout inutilizzate **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Mantiene solo i glifi effettivamente usati nei font incorporati **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Riduce la risoluzione delle immagini a 150 DPI ed elimina le aree ritagliate delle immagini **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione da comprimere. |

### Osservazioni

Per personalizzare la compressione, ad esempio per utilizzare una risoluzione immagine diversa o per saltare un passaggio, chiamare i metodi elencati sopra singolarmente anziché questo. Le aree ritagliate delle immagini vengono rimosse in modo permanente e non possono essere ripristinate in PowerPoint.

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` è `None`. |

### Vedi anche
* classe [`Compress`](/slides/python-net/it/aspose.slides.lowcode/compress)
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* libreria [`Aspose.Slides`](/slides/python-net)
---
title: compress_images method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Riduce la risoluzione delle immagini nella presentazione ed elimina le loro aree ritagliate,
            simile alla funzione "Compress Pictures" di PowerPoint applicata a tutte le immagini.
            Le immagini nelle diapositive, nelle diapositive di layout e nelle diapositive master vengono elaborate, incluse le immagini all'interno di forme raggruppate
            e i riempimenti immagine delle forme.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) | La presentazione da elaborare. |
| resolution | [`PicturesCompression`](/slides/python-net/it/aspose.slides.export/picturescompression) | Risoluzione target relativa alle dimensioni con cui ogni immagine viene visualizzata.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/it/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) lascia le immagini inalterate. |

### Osservazioni

Le immagini già alla risoluzione target o inferiore vengono lasciate inalterate; le immagini non vengono mai ingrandite.

Non elaborate: sfondi delle diapositive, riempimenti delle celle di tabella, grafici, SmartArt, immagini GIF (per preservare l'animazione),
            immagini SVG e metafile (EMF/WMF).

Le aree ritagliate vengono rimosse definitivamente e non possono essere ripristinate in PowerPoint.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` è `None`. |

### Vedi anche
* classe [`Compress`](/slides/python-net/it/aspose.slides.lowcode/compress)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* enumerazione [`PicturesCompression`](/slides/python-net/it/aspose.slides.export/picturescompression)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* libreria [`Aspose.Slides`](/slides/python-net)
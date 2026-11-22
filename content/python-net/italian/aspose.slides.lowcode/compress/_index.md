---
title: Compress class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.lowcode/compress/
---
## Compress classe

Rappresenta un gruppo di metodi destinati a comprimere [`Presentation`](/slides/python-net/it/aspose.slides/presentation).

Il tipo Compress espone i seguenti membri:

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/it/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Riduce le dimensioni di una presentazione applicando tutti i passaggi di compressione disponibili:<br/>            <br/>* Rimuove le diapositive master non utilizzate **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Rimuove le diapositive layout non utilizzate **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Mantiene solo i glifi effettivamente utilizzati nei font incorporati **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Riduce la risoluzione delle immagini a 150 DPI ed elimina le aree ritagliate delle immagini **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/it/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Effettua la compressione del [`Presentation`](/slides/python-net/it/aspose.slides/presentation) rimuovendo le diapositive master non utilizzate. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/it/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Effettua la compressione del [`Presentation`](/slides/python-net/it/aspose.slides/presentation) rimuovendo le diapositive layout non utilizzate. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/it/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Effettua la compressione del [`Presentation`](/slides/python-net/it/aspose.slides/presentation) rimuovendo i caratteri non utilizzati dai font incorporati. |
| [`compress_images(presentation, resolution)`](/slides/python-net/it/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Riduce la risoluzione delle immagini nella presentazione ed elimina le loro aree ritagliate,<br/>            simile a "Compress Pictures" di PowerPoint applicato a tutte le immagini.<br/>            Le immagini nelle diapositive, nelle diapositive layout e nelle diapositive master vengono elaborate, comprese le immagini all'interno di forme di gruppo<br/>            e i riempimenti di immagine delle forme. |


### Vedi anche
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* libreria [`Aspose.Slides`](/slides/python-net)
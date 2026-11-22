---
title: Compress class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.lowcode/compress/
---
## Compress classe

Représente un groupe de méthodes destinées à compresser [`Presentation`](/slides/python-net/fr/aspose.slides/presentation).

Le type Compress expose les membres suivants :

## Méthodes

| Méthode | Description |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/fr/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Réduit la taille d’une présentation en appliquant toutes les étapes de compression disponibles:<br/>            <br/>* Supprime les diapositives maîtres inutilisées **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Supprime les diapositives de mise en page inutilisées **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Conserve uniquement les glyphes réellement utilisés dans les polices incorporées **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Réduit la résolution des images à 150 DPI et supprime les zones recadrées des images **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/fr/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Réalise la compression du [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) en supprimant les diapositives maîtres inutilisées. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/fr/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Réalise la compression du [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) en supprimant les diapositives de mise en page inutilisées. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/fr/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Réalise la compression du [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) en supprimant les caractères inutilisés des polices incorporées. |
| [`compress_images(presentation, resolution)`](/slides/python-net/fr/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Réduit la résolution des images dans la présentation et supprime leurs zones recadrées,<br/>            similaire à la fonction "Compress Pictures" de PowerPoint appliquée à toutes les images.<br/>            Les images sur les diapositives, les diapositives de mise en page et les diapositives maîtres sont traitées, y compris les images à l’intérieur des formes groupées<br/>            et les remplissages d’image des formes. |


### Voir aussi
* classe [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/fr/aspose.slides.lowcode)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
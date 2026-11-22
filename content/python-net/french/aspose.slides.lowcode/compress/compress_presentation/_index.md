---
title: compress_presentation method
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Réduit la taille d'une présentation en appliquant toutes les étapes de compression disponibles :

* Supprime les diapositives maîtres inutilisées **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Supprime les diapositives de mise en page inutilisées **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Ne conserve que les glyphes réellement utilisés dans les polices incorporées **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Réduit la résolution des images à 150 DPI et supprime les zones recadrées des images **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/fr/aspose.slides/presentation) | La présentation à compresser. |

### Remarques

Pour personnaliser la compression, par exemple pour utiliser une résolution d'image différente ou pour ignorer une étape, appelez les méthodes répertoriées ci-dessus individuellement au lieu de celle-ci. Les zones recadrées des images sont supprimées de façon permanente et ne peuvent pas être restaurées dans PowerPoint.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` est `None`. |

### Voir aussi
* classe [`Compress`](/slides/python-net/fr/aspose.slides.lowcode/compress)
* classe [`Presentation`](/slides/python-net/fr/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/fr/aspose.slides.lowcode)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
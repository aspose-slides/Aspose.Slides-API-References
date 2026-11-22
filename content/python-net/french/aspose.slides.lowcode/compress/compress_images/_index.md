---
title: compress_images method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Réduit la résolution des images dans la présentation et supprime leurs zones rognées,
            similaire à la fonction "Compress Pictures" de PowerPoint appliquée à toutes les images.
            Les images sur les diapositives, les diapositives de mise en page et les diapositives maîtres sont traitées, y compris les images à l'intérieur des formes groupées
            et les remplissages d'images des formes.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation) | La présentation à traiter. |
| resolution | [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression) | Résolution cible relative à la taille à laquelle chaque image est affichée.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/fr/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) laisse les images inchangées. |

### Remarques

Les images déjà à la résolution cible ou en dessous restent inchangées ; les images ne sont jamais agrandies.

Non traités : arrière-plans des diapositives, remplissages des cellules de tableau, graphiques, SmartArt, images GIF (pour préserver l'animation),
            images SVG et métafichiers (EMF/WMF).

Les zones rognées sont supprimées de façon permanente et ne peuvent pas être restaurées dans PowerPoint.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` est `None`. |



### Voir aussi
* classe [`Compress`](/slides/python-net/fr/aspose.slides.lowcode/compress)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* énumération [`PicturesCompression`](/slides/python-net/fr/aspose.slides.export/picturescompression)
* module [`aspose.slides.lowcode`](/slides/python-net/fr/aspose.slides.lowcode)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
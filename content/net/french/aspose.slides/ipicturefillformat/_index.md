---
title: IPictureFillFormat
second_title: Référence API Aspose.Slides pour .NET
description: Représente un style de remplissage d'image.
type: docs
weight: 6450
url: /fr/aspose.slides/ipicturefillformat/
---

## Interface IPictureFillFormat

Représente un style de remplissage d'image.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Permet d'obtenir l'interface de base IFillParamSource. Lecture seule [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est rogné au bas de l'image. Lecture/écriture Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est rogné à gauche de l'image. Lecture/écriture Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est rogné à droite de l'image. Lecture/écriture Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est rogné en haut de l'image. Lecture/écriture Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Renvoie ou définit le dpi qui est utilisé pour remplir une image. Lecture/écriture Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Renvoie l'image. Lecture seule [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Renvoie ou définit le mode de remplissage de l'image. Lecture/écriture [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Renvoie ou définit le bord inférieur du rectangle de remplissage qui est défini par un décalage en pourcentage à partir du bord inférieur de la boîte englobante de la forme. Un pourcentage positif spécifie un retrait, tandis qu'un pourcentage négatif spécifie un dépassement. Lecture/écriture Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Renvoie ou définit le bord gauche du rectangle de remplissage qui est défini par un décalage en pourcentage à partir du bord gauche de la boîte englobante de la forme. Un pourcentage positif spécifie un retrait, tandis qu'un pourcentage négatif spécifie un dépassement. Lecture/écriture Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Renvoie ou définit le bord droit du rectangle de remplissage qui est défini par un décalage en pourcentage à partir du bord droit de la boîte englobante de la forme. Un pourcentage positif spécifie un retrait, tandis qu'un pourcentage négatif spécifie un dépassement. Lecture/écriture Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Renvoie ou définit le bord supérieur du rectangle de remplissage qui est défini par un décalage en pourcentage à partir du bord supérieur de la boîte englobante de la forme. Un pourcentage positif spécifie un retrait, tandis qu'un pourcentage négatif spécifie un dépassement. Lecture/écriture Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Renvoie ou définit la manière dont la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la manière dont il se répète sur la forme. Lecture/écriture [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Lecture/écriture [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Renvoie ou définit le décalage horizontal de la texture à partir de l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture/écriture Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Renvoie ou définit le décalage vertical de la texture à partir de l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture/écriture Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Renvoie ou définit l'échelle horizontale pour le remplissage de texture en pourcentage. Lecture/écriture Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Renvoie ou définit l'échelle verticale pour le remplissage de texture en pourcentage. Lecture/écriture Single. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. En option, elle supprime également les zones rognées. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. En option, elle supprime également les zones rognées. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Supprime les zones rognées de l'image de remplissage. |

### Voir aussi

* interface [IFillParamSource](../ifillparamsource)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
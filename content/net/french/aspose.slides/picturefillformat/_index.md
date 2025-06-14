---
title: PictureFillFormat
second_title: Aspose.Sildes pour .NET Référence API
description: Représente un style de remplissage par image.
type: docs
weight: 9120
url: /fr/aspose.slides/picturefillformat/
---

## PictureFillFormat class

Représente un style de remplissage par image.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. En lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Renvoie ou définit le nombre de pourcents de la hauteur réelle de l'image qui sont recadrés en bas de l'image. Lecture/écriture Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Renvoie ou définit le nombre de pourcents de la largeur réelle de l'image qui sont recadrés à gauche de l'image. Lecture/écriture Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Renvoie ou définit le nombre de pourcents de la largeur réelle de l'image qui sont recadrés à droite de l'image. Lecture/écriture Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Renvoie ou définit le nombre de pourcents de la hauteur réelle de l'image qui sont recadrés en haut de l'image. Lecture/écriture Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Renvoie ou définit le dpi qui est utilisé pour remplir une image. Lecture/écriture Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Renvoie l'image. En lecture seule [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Renvoie ou définit le mode de remplissage par image. Lecture/écriture [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Renvoie ou définit le bord inférieur du rectangle de remplissage qui est défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif spécifie un décalage intérieur, tandis qu'un pourcentage négatif spécifie un décalage extérieur. Lecture/écriture Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Renvoie ou définit le bord gauche du rectangle de remplissage qui est défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif spécifie un décalage intérieur, tandis qu'un pourcentage négatif spécifie un décalage extérieur. Lecture/écriture Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Renvoie ou définit le bord droit du rectangle de remplissage qui est défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif spécifie un décalage intérieur, tandis qu'un pourcentage négatif spécifie un décalage extérieur. Lecture/écriture Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Renvoie ou définit le bord supérieur du rectangle de remplissage qui est défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif spécifie un décalage intérieur, tandis qu'un pourcentage négatif spécifie un décalage extérieur. Lecture/écriture Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Renvoie ou définit comment la texture est alignée dans la forme. Ce paramètre contrôle le point de départ du motif de texture et comment il se répète sur la forme. Lecture/écriture [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Retourne le carreau de texture autour de son axe horizontal, vertical ou les deux. Lecture/écriture [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Renvoie ou définit le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture/écriture Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Renvoie ou définit le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture/écriture Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Renvoie ou définit l'échelle horizontale pour le remplissage de texture en pourcentage. Lecture/écriture Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Renvoie ou définit l'échelle verticale pour le remplissage de texture en pourcentage. Lecture/écriture Single. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. En option, elle supprime également les zones recadrées. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. En option, elle supprime également les zones recadrées. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Supprime les zones recadrées du remplissage par image. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir aussi

* class [PVIObject](../pviobject)
* interface [IPictureFillFormat](../ipicturefillformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
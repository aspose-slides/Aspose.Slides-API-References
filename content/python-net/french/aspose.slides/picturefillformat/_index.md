---
title: PictureFillFormat class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/picturefillformat/
---
## PictureFillFormat classe

Représente un style de remplissage d'image.

**Héritage:**[`PictureFillFormat`](/slides/python-net/fr/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type PictureFillFormat expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/fr/aspose.slides/picturefillformat/dpi/) | Renvoie ou définit le DPI utilisé pour remplir une image.<br/>            Lecture/écriture **int**. |
| [`picture_fill_mode`](/slides/python-net/fr/aspose.slides/picturefillformat/picture_fill_mode/) | Renvoie ou définit le mode de remplissage d'image.<br/>            Lecture/écriture [`PictureFillMode`](/slides/python-net/fr/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/fr/aspose.slides/picturefillformat/picture/) | Renvoie l'image.<br/>            Lecture seule [`ISlidesPicture`](/slides/python-net/fr/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/fr/aspose.slides/picturefillformat/crop_left/) | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont recadrés du côté gauche de l'image.<br/>            Lecture/écriture **float**. |
| [`crop_top`](/slides/python-net/fr/aspose.slides/picturefillformat/crop_top/) | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont recadrés du côté supérieur de l'image.<br/>            Lecture/écriture **float**. |
| [`crop_right`](/slides/python-net/fr/aspose.slides/picturefillformat/crop_right/) | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont recadrés du côté droit de l'image.<br/>            Lecture/écriture **float**. |
| [`crop_bottom`](/slides/python-net/fr/aspose.slides/picturefillformat/crop_bottom/) | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont recadrés du côté inférieur de l'image.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_left`](/slides/python-net/fr/aspose.slides/picturefillformat/stretch_offset_left/) | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage <br/>            depuis le bord gauche de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extrusion.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_top`](/slides/python-net/fr/aspose.slides/picturefillformat/stretch_offset_top/) | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage <br/>            depuis le bord supérieur de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extrusion.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_right`](/slides/python-net/fr/aspose.slides/picturefillformat/stretch_offset_right/) | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage <br/>            depuis le bord droit de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extrusion.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_bottom`](/slides/python-net/fr/aspose.slides/picturefillformat/stretch_offset_bottom/) | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage <br/>            depuis le bord inférieur de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une extrusion.<br/>            Lecture/écriture **float**. |
| [`tile_offset_x`](/slides/python-net/fr/aspose.slides/picturefillformat/tile_offset_x/) | Renvoie ou définit le décalage horizontal de la texture par rapport à l'origine de la forme en points.<br/>             Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche.<br/>             Lecture/écriture **float**. |
| [`tile_offset_y`](/slides/python-net/fr/aspose.slides/picturefillformat/tile_offset_y/) | Renvoie ou définit le décalage vertical de la texture par rapport à l'origine de la forme en points.<br/>             Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut.<br/>             Lecture/écriture **float**. |
| [`tile_scale_x`](/slides/python-net/fr/aspose.slides/picturefillformat/tile_scale_x/) | Renvoie ou définit l'échelle horizontale du remplissage de texture en pourcentage.<br/>             Lecture/écriture **float**. |
| [`tile_scale_y`](/slides/python-net/fr/aspose.slides/picturefillformat/tile_scale_y/) | Renvoie ou définit l'échelle verticale du remplissage de texture en pourcentage.<br/>             Lecture/écriture **float**. |
| [`tile_alignment`](/slides/python-net/fr/aspose.slides/picturefillformat/tile_alignment/) | Renvoie ou définit comment la texture est alignée dans la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète dans la forme.<br/>             Lecture/écriture [`RectangleAlignment`](/slides/python-net/fr/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/fr/aspose.slides/picturefillformat/tile_flip/) | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux.<br/>             Lecture/écriture [`TileFlip`](/slides/python-net/fr/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/fr/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/picturefillformat/presentation/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/fr/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/fr/aspose.slides/picturefillformat/compress_image/#bool-float) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/fr/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | Supprime les zones recadrées de l'image de remplissage. |

### Voir aussi
* classe [`PictureFillFormat`](/slides/python-net/fr/aspose.slides/picturefillformat)
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
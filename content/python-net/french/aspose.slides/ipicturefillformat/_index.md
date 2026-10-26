---
title: IPictureFillFormat class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat classe

Représente un style de remplissage par image.

Le type IPictureFillFormat expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/fr/aspose.slides/ipicturefillformat/dpi/) | Renvoie ou définit le dpi utilisé pour remplir une image.<br/>            Lecture/écriture **int**. |
| [`picture_fill_mode`](/slides/python-net/fr/aspose.slides/ipicturefillformat/picture_fill_mode/) | Renvoie ou définit le mode de remplissage de l'image.<br/>            Lecture/écriture [`PictureFillMode`](/slides/python-net/fr/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/fr/aspose.slides/ipicturefillformat/picture/) | Renvoie l'image.<br/>            Lecture seule [`ISlidesPicture`](/slides/python-net/fr/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/fr/aspose.slides/ipicturefillformat/crop_left/) | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont rognés du côté gauche de l'image.<br/>            Lecture/écriture **float**. |
| [`crop_top`](/slides/python-net/fr/aspose.slides/ipicturefillformat/crop_top/) | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont rognés du côté supérieur de l'image.<br/>            Lecture/écriture **float**. |
| [`crop_right`](/slides/python-net/fr/aspose.slides/ipicturefillformat/crop_right/) | Renvoie ou définit le nombre de pourcentages de la largeur réelle de l'image qui sont rognés du côté droit de l'image.<br/>            Lecture/écriture **float**. |
| [`crop_bottom`](/slides/python-net/fr/aspose.slides/ipicturefillformat/crop_bottom/) | Renvoie ou définit le nombre de pourcentages de la hauteur réelle de l'image qui sont rognés du côté inférieur de l'image.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_left`](/slides/python-net/fr/aspose.slides/ipicturefillformat/stretch_offset_left/) | Renvoie ou définit le bord gauche du rectangle de remplissage qui est défini par un décalage en pourcentage par rapport au bord gauche de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une proéminence.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_top`](/slides/python-net/fr/aspose.slides/ipicturefillformat/stretch_offset_top/) | Renvoie ou définit le bord supérieur du rectangle de remplissage qui est défini par un décalage en pourcentage par rapport au bord supérieur de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une proéminence.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_right`](/slides/python-net/fr/aspose.slides/ipicturefillformat/stretch_offset_right/) | Renvoie ou définit le bord droit du rectangle de remplissage qui est défini par un décalage en pourcentage par rapport au bord droit de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une proéminence.<br/>            Lecture/écriture **float**. |
| [`stretch_offset_bottom`](/slides/python-net/fr/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Renvoie ou définit le bord inférieur du rectangle de remplissage qui est défini par un décalage en pourcentage par rapport au bord inférieur de la boîte englobante de la forme.<br/>            Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique une proéminence.<br/>            Lecture/écriture **float**. |
| [`tile_offset_x`](/slides/python-net/fr/aspose.slides/ipicturefillformat/tile_offset_x/) | Renvoie ou définit le décalage horizontal de la texture par rapport à l'origine de la forme en points.<br/>            Une valeur positive déplace la texture vers la droite, une valeur négative la déplace vers la gauche.<br/>            Lecture/écriture **float**. |
| [`tile_offset_y`](/slides/python-net/fr/aspose.slides/ipicturefillformat/tile_offset_y/) | Renvoie ou définit le décalage vertical de la texture par rapport à l'origine de la forme en points.<br/>            Une valeur positive déplace la texture vers le bas, une valeur négative la déplace vers le haut.<br/>            Lecture/écriture **float**. |
| [`tile_scale_x`](/slides/python-net/fr/aspose.slides/ipicturefillformat/tile_scale_x/) | Renvoie ou définit l'échelle horizontale de la texture de remplissage en pourcentage.<br/>            Lecture/écriture **float**. |
| [`tile_scale_y`](/slides/python-net/fr/aspose.slides/ipicturefillformat/tile_scale_y/) | Renvoie ou définit l'échelle verticale de la texture de remplissage en pourcentage.<br/>            Lecture/écriture **float**. |
| [`tile_alignment`](/slides/python-net/fr/aspose.slides/ipicturefillformat/tile_alignment/) | Renvoie ou définit la façon dont la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la manière dont il se répète sur la forme.<br/>            Lecture/écriture [`RectangleAlignment`](/slides/python-net/fr/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/fr/aspose.slides/ipicturefillformat/tile_flip/) | Retourne la tuile de texture en la retournant autour de son axe horizontal, vertical ou les deux.<br/>            Lecture/écriture [`TileFlip`](/slides/python-net/fr/aspose.slides/tileflip). |

## Méthodes

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/fr/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, supprime également les zones rognées. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/fr/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, supprime également les zones rognées. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/fr/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Supprime les zones rognées de l'image de remplissage. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
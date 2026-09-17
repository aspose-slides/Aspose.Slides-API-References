---
title: PPImage class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ppimage/
---
## PPImage classe

Représente une image dans une présentation.

Le type PPImage expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/fr/aspose.slides/ppimage/binary_data/) | Renvoie la copie des données d'une image.<br/>            Read-only **int**[]. |
| [`image`](/slides/python-net/fr/aspose.slides/ppimage/image/) | Renvoie la copie d'une image.<br/>            Read-only [`IImage`](/slides/python-net/fr/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/fr/aspose.slides/ppimage/svg_image/) | Renvoie ou définit l'objet ISvgImage [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/fr/aspose.slides/ppimage/content_type/) | Renvoie le type MIME d'une image, encodé en [`PPImage.binary_data`](/slides/python-net/fr/aspose.slides/ppimage/binary_data).<br/>            Read-only **str**. |
| [`width`](/slides/python-net/fr/aspose.slides/ppimage/width/) | Renvoie la largeur d'une image.<br/>            Read-only **int**. |
| [`height`](/slides/python-net/fr/aspose.slides/ppimage/height/) | Renvoie la hauteur d'une image.<br/>            Read-only **int**. |
| [`x`](/slides/python-net/fr/aspose.slides/ppimage/x/) | Renvoie le décalage X d'une image.<br/>            Read-only **int**. |
| [`y`](/slides/python-net/fr/aspose.slides/ppimage/y/) | Renvoie le décalage Y d'une image.<br/>            Read-only **int**. |

## Méthodes

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/fr/aspose.slides/ppimage/replace_image/#bytes) | Remplace les données de l'image.<br/>            Les nouvelles données de l'image.Quand le paramètre newImageData est None. |
| [`replace_image(self, new_image)`](/slides/python-net/fr/aspose.slides/ppimage/replace_image/#iimage) | Remplace les données de l'image. Attention : lorsque l'image est un métafichier - elle sera rasterisée. Utilisez ReplaceImage(byte[]) à la place<br/>            La nouvelle image.Quand le paramètre newImage est None. |
| [`replace_image(self, new_image)`](/slides/python-net/fr/aspose.slides/ppimage/replace_image/#ippimage) | Remplace les données de l'image.<br/>            Le nouveau IPPImage.Quand le paramètre newImage est None. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
---
title: IBulletFormat class
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides/ibulletformat/
---
## IBulletFormat class

Représente les propriétés de mise en forme des puces de paragraphe.

Le type IBulletFormat expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/fr/aspose.slides/ibulletformat/type/) | Renvoie ou définit le type de puce d'un paragraphe sans héritage.<br/>            Lecture/écriture [`BulletType`](/slides/python-net/fr/aspose.slides/bullettype). |
| [`char`](/slides/python-net/fr/aspose.slides/ibulletformat/char/) | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage.<br/>            Lecture/écriture **System.Char**. |
| [`font`](/slides/python-net/fr/aspose.slides/ibulletformat/font/) | Renvoie ou définit la police de puce d'un paragraphe sans héritage.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/fr/aspose.slides/ibulletformat/height/) | Renvoie ou définit la hauteur de la puce d'un paragraphe sans héritage.<br/>            La valeur float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe.<br/>            Lecture/écriture **float**. |
| [`color`](/slides/python-net/fr/aspose.slides/ibulletformat/color/) | Renvoie le format de couleur d'une puce d'un paragraphe sans héritage.<br/>            Lecture seule [`IColorFormat`](/slides/python-net/fr/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/fr/aspose.slides/ibulletformat/picture/) | Renvoie l'image utilisée comme puce dans un paragraphe sans héritage.<br/>            Lecture seule [`ISlidesPicture`](/slides/python-net/fr/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/fr/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage.<br/>            Lecture/écriture **int**. |
| [`numbered_bullet_style`](/slides/python-net/fr/aspose.slides/ibulletformat/numbered_bullet_style/) | Renvoie ou définit le style d'une puce numérotée sans héritage.<br/>            Lecture/écriture [`IBulletFormat.numbered_bullet_style`](/slides/python-net/fr/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/fr/aspose.slides/ibulletformat/is_bullet_hard_color/) | Détermine si la puce a sa propre couleur ou l'hérite de la première portion du paragraphe.<br/>            **NullableBool.True** si la puce a sa propre couleur et **NullableBool.False** si la puce<br/>            hérite de la couleur de la première portion du paragraphe.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/fr/aspose.slides/ibulletformat/is_bullet_hard_font/) | Détermine si la puce a sa propre police ou l'hérite de la première portion du paragraphe.<br/>            **NullableBool.True** si la puce a sa propre police et **NullableBool.False** si la puce<br/>            hérite de la police de la première portion du paragraphe.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |

## Méthodes

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/fr/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Définit les décalages non nuls par défaut pour l'Indent et le MarginLeft effectifs du paragraphe lorsque les puces sont activées (comme le fait PowerPoint si l'on active les puces/la numérotation du paragraphe). Si les puces sont désactivées, réinitialise simplement l'Indent et le MarginLeft du paragraphe (comme le fait PowerPoint si l'on désactive les puces/la numérotation du paragraphe). Les décalages d'indentation sont appliqués en fonction du contexte actuel de la puce – IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indent et au MarginLeft effectifs du paragraphe actuel (rendant les valeurs résultantes locales). |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/ibulletformat/get_effective/#) | Obtient les données de mise en forme effectives de la puce avec l'héritage appliqué. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
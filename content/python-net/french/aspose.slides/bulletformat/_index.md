---
title: BulletFormat class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/bulletformat/
---
## classe BulletFormat

Représente les propriétés de formatage des puces de paragraphe.

**Héritage:**[`BulletFormat`](/slides/python-net/fr/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type BulletFormat expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`type`](/slides/python-net/fr/aspose.slides/bulletformat/type/) | Renvoie ou définit le type de puce d'un paragraphe sans héritage.<br/>            Lecture/écriture [`BulletType`](/slides/python-net/fr/aspose.slides/bullettype). |
| [`char`](/slides/python-net/fr/aspose.slides/bulletformat/char/) | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage.<br/>            Lecture/écriture **System.Char**. |
| [`font`](/slides/python-net/fr/aspose.slides/bulletformat/font/) | Renvoie ou définit la police de la puce d'un paragraphe sans héritage.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/fr/aspose.slides/bulletformat/height/) | Renvoie ou définit la hauteur de la puce d'un paragraphe sans héritage.<br/>            La valeur float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe.<br/>            Lecture/écriture **float**. |
| [`color`](/slides/python-net/fr/aspose.slides/bulletformat/color/) | Renvoie le format de couleur d'une puce d'un paragraphe sans héritage.<br/>            Lecture seule [`IColorFormat`](/slides/python-net/fr/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/fr/aspose.slides/bulletformat/numbered_bullet_start_with/) | Renvoie ou définit le premier numéro utilisé pour le groupe de puces numérotées sans héritage.<br/>            Lecture/écriture **int**. |
| [`numbered_bullet_style`](/slides/python-net/fr/aspose.slides/bulletformat/numbered_bullet_style/) | Renvoie ou définit le style d'une puce numérotée sans héritage.<br/>            Lecture/écriture [`NumberedBulletStyle`](/slides/python-net/fr/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/fr/aspose.slides/bulletformat/is_bullet_hard_color/) | Détermine si la puce possède sa propre couleur ou l'hérite de la première portion du paragraphe.<br/>            **NullableBool.True**  si la puce a sa propre couleur et **NullableBool.False**  si la puce<br/>            hérite de la couleur de la première portion du paragraphe.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/fr/aspose.slides/bulletformat/is_bullet_hard_font/) | Détermine si la puce possède sa propre police ou l'hérite de la première portion du paragraphe.<br/>            **NullableBool.True**  si la puce a sa propre police et **NullableBool.False**  si la puce<br/>            hérite de la police de la première portion du paragraphe.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/fr/aspose.slides/bulletformat/picture/) | Renvoie l'image utilisée comme puce dans un paragraphe sans héritage.<br/>            Lecture seule [`ISlidesPicture`](/slides/python-net/fr/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/fr/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/bulletformat/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/fr/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Définit les décalages par défaut non nuls pour l'Indent et le MarginLeft effectifs du paragraphe lorsque les puces sont activées (comme PowerPoint le fait si l’on active les puces/la numérotation de paragraphe). Si les puces sont désactivées, réinitialise simplement l'Indent et le MarginLeft du paragraphe (comme PowerPoint le fait si l’on désactive les puces/la numérotation). Les décalages d'indentation sont appliqués en fonction du contexte actuel de la puce – IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indent et au MarginLeft effectifs du paragraphe actuel (rendant les valeurs résultantes locales). |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/bulletformat/get_effective/#) | Obtient les données de formatage effectif des puces avec l'héritage appliqué. |


### Voir aussi
* classe [`BulletFormat`](/slides/python-net/fr/aspose.slides/bulletformat)
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
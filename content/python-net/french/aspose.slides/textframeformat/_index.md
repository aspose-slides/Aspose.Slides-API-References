---
title: TextFrameFormat class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contient les propriétés de formatage TextFrameFormatting du TextFrame.

**Héritage:**[`TextFrameFormat`](/slides/python-net/fr/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type TextFrameFormat expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/textframeformat/__init__/#) | Initialise une nouvelle instance de la classe [`TextFrameFormat`](/slides/python-net/fr/aspose.slides/textframeformat). |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/textframeformat/three_d_format/) | Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3d pour un texte.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/fr/aspose.slides/textframeformat/margin_left/) | Renvoie ou définit la marge gauche (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_right`](/slides/python-net/fr/aspose.slides/textframeformat/margin_right/) | Renvoie ou définit la marge droite (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_top`](/slides/python-net/fr/aspose.slides/textframeformat/margin_top/) | Renvoie ou définit la marge supérieure (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_bottom`](/slides/python-net/fr/aspose.slides/textframeformat/margin_bottom/) | Renvoie ou définit la marge inférieure (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`wrap_text`](/slides/python-net/fr/aspose.slides/textframeformat/wrap_text/) | **True**  si le texte est renvoyé à la ligne aux marges du TextFrame.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/fr/aspose.slides/textframeformat/anchoring_type/) | Renvoie ou définit l'ancre verticale du texte dans un TextFrame.<br/>            Lecture/écriture [`TextAnchorType`](/slides/python-net/fr/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/fr/aspose.slides/textframeformat/center_text/) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/fr/aspose.slides/textframeformat/text_vertical_type/) | Détermine l'orientation du texte.<br/>            La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l'angle personnalisé<br/>            dans la propriété RotationAngle.<br/>            Lecture/écriture [`TextVerticalType`](/slides/python-net/fr/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/fr/aspose.slides/textframeformat/autofit_type/) | Renvoie ou définit le mode d'ajustement automatique du texte.<br/>            Lecture/écriture [`TextAutofitType`](/slides/python-net/fr/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/fr/aspose.slides/textframeformat/column_count/) | Renvoie ou définit le nombre de colonnes dans la zone de texte.<br/>            Cette valeur doit être un nombre positif. Sinon, la valeur sera réglée à zéro. <br/>            La valeur 0 signifie valeur indéfinie.<br/>            Lecture/écriture **int**. |
| [`column_spacing`](/slides/python-net/fr/aspose.slides/textframeformat/column_spacing/) | Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne s'applique que <br/>            lorsqu'il y a plus d'une colonne présente.<br/>            Cette valeur doit être un nombre positif. Sinon, la valeur sera réglée à zéro. <br/>            Lecture/écriture **float**. |
| [`rotation_angle`](/slides/python-net/fr/aspose.slides/textframeformat/rotation_angle/) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas<br/>            spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, alors elle est<br/>            appliquée indépendamment de la forme. Autrement dit, la forme peut avoir une rotation appliquée en<br/>            plus de la rotation appliquée au texte lui-même.<br/>            La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et du type<br/>            vertical prédéfini dans la propriété TextVerticalType.<br/>            Lecture/écriture **float**. |
| [`transform`](/slides/python-net/fr/aspose.slides/textframeformat/transform/) | Obtient ou définit la forme d'habillage du texte.<br/>            Lecture/écriture [`TextShapeType`](/slides/python-net/fr/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/fr/aspose.slides/textframeformat/keep_text_flat/) | Obtient ou définit le fait de garder le texte plat même si un effet de rotation 3-D a été appliqué.<br/>            Lecture/écriture **bool**. |
| [`slide`](/slides/python-net/fr/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/fr/aspose.slides/textframeformat/text_style/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/textframeformat/get_effective/#) | Obtient les données de formatage effectif du cadre de texte avec l'héritage appliqué. |


### Voir aussi
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* classe [`TextFrameFormat`](/slides/python-net/fr/aspose.slides/textframeformat)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
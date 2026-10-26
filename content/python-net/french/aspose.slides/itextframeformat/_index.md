---
title: ITextFrameFormat class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/itextframeformat/
---
## ITextFrameFormat classe

Contains the TextFrame's formatting properties.

The ITextFrameFormat type exposes the following members:

## Propriétés

| Propriété | Description |
| :- | :- |
| [`text_style`](/slides/python-net/fr/aspose.slides/itextframeformat/text_style/) | Renvoie le style du texte.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/fr/aspose.slides/itextframeformat/margin_left/) | Renvoie ou définit la marge gauche (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_right`](/slides/python-net/fr/aspose.slides/itextframeformat/margin_right/) | Renvoie ou définit la marge droite (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_top`](/slides/python-net/fr/aspose.slides/itextframeformat/margin_top/) | Renvoie ou définit la marge supérieure (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_bottom`](/slides/python-net/fr/aspose.slides/itextframeformat/margin_bottom/) | Renvoie ou définit la marge inférieure (points) dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`wrap_text`](/slides/python-net/fr/aspose.slides/itextframeformat/wrap_text/) | **True** si le texte est renvoyé aux marges du TextFrame.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/fr/aspose.slides/itextframeformat/anchoring_type/) | Renvoie ou définit l'ancre verticale du texte dans un TextFrame.<br/>            Lecture/écriture [`TextAnchorType`](/slides/python-net/fr/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/fr/aspose.slides/itextframeformat/center_text/) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/fr/aspose.slides/itextframeformat/text_vertical_type/) | Détermine l'orientation du texte.<br/>            La valeur résultante de la rotation visuelle du texte résumée de cette propriété et de l'angle personnalisé<br/>            dans la propriété RotationAngle.<br/>            Lecture/écriture [`TextVerticalType`](/slides/python-net/fr/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/fr/aspose.slides/itextframeformat/autofit_type/) | Renvoie ou définit le mode d'ajustement automatique du texte.<br/>            Lecture/écriture [`TextAutofitType`](/slides/python-net/fr/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/fr/aspose.slides/itextframeformat/column_count/) | Renvoie ou définit le nombre de colonnes dans la zone de texte.<br/>            Cette valeur doit être un nombre positif. Sinon, la valeur sera définie à zéro. <br/>            La valeur 0 signifie valeur non définie.<br/>            Lecture/écriture **int**. |
| [`column_spacing`](/slides/python-net/fr/aspose.slides/itextframeformat/column_spacing/) | Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Ceci ne doit s'appliquer que <br/>            lorsqu'il y a plus d'une colonne présente.<br/>            Cette valeur doit être un nombre positif. Sinon, la valeur sera définie à zéro. <br/>            Lecture/écriture **float**. |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/itextframeformat/three_d_format/) | Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3d pour un texte.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/fr/aspose.slides/itextframeformat/keep_text_flat/) | Renvoie ou définit le fait de garder le texte hors de la scène 3D entièrement.<br/>            Lecture/écriture **bool**. |
| [`rotation_angle`](/slides/python-net/fr/aspose.slides/itextframeformat/rotation_angle/) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas<br/>            spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est alors<br/>            appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en<br/>            plus de la rotation appliquée au texte lui-même.<br/>            La valeur résultante de la rotation visuelle du texte résumée de cette propriété et du type<br/>            vertical prédéfini dans la propriété TextVerticalType.<br/>            Lecture/écriture **float**. |
| [`transform`](/slides/python-net/fr/aspose.slides/itextframeformat/transform/) | Renvoie ou définit la forme d'habillage du texte.<br/>            Lecture/écriture [`TextShapeType`](/slides/python-net/fr/aspose.slides/textshapetype). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/itextframeformat/get_effective/#) | Renvoie les données de mise en forme effectives du cadre de texte avec l'héritage appliqué. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
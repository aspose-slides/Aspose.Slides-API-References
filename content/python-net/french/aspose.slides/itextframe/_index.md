---
title: ITextFrame class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/itextframe/
---
## ITextFrame classe

Représente un TextFrame.

Le type ITextFrame expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/fr/aspose.slides/itextframe/paragraphs/) | Renvoie la liste de tous les paragraphes dans un cadre.<br/>            Lecture seule [`IParagraphCollection`](/slides/python-net/fr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fr/aspose.slides/itextframe/text/) | Obtient ou définit le texte brut pour un TextFrame.<br/>            Lecture/écriture **str**. |
| [`text_frame_format`](/slides/python-net/fr/aspose.slides/itextframe/text_frame_format/) | Renvoie l'objet de formatage pour cet objet TextFrame.<br/>            Lecture seule [`ITextFrameFormat`](/slides/python-net/fr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/itextframe/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/fr/aspose.slides/itextframe/parent_shape/) | Renvoie la forme parent ou None si l'objet parent n'implémente pas l'interface IShape<br/>            Lecture seule [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fr/aspose.slides/itextframe/parent_cell/) | Renvoie la cellule parent ou None si l'objet parent n'implémente pas l'interface ICell.<br/>            Lecture seule [`ICell`](/slides/python-net/fr/aspose.slides/icell). |
| [`slide`](/slides/python-net/fr/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/itextframe/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fr/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fr/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fr/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [`get_text_rect(self)`](/slides/python-net/fr/aspose.slides/itextframe/get_text_rect/#) | Obtient le rectangle de texte défini par la géométrie de la forme parent. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Fusionne les runs avec le même formatage dans tous les paragraphes. |
| [`split_text_by_columns(self)`](/slides/python-net/fr/aspose.slides/itextframe/split_text_by_columns/#) | Divise le contenu texte du [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe) en un tableau de chaînes, <br/>            où chaque élément correspond à une colonne texte distincte dans le cadre. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fr/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fr/aspose.slides/itextframe/replace_regex/#str-str) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
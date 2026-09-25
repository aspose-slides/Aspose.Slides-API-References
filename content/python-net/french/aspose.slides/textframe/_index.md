---
title: TextFrame class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/textframe/
---
## TextFrame classe

Represents a TextFrame.

The TextFrame type exposes the following members:

## Propriétés

| Propriété | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/fr/aspose.slides/textframe/paragraphs/) | Renvoie la liste de tous les paragraphes d'un cadre.<br/>            Lecture seule [`IParagraphCollection`](/slides/python-net/fr/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fr/aspose.slides/textframe/text/) | Obtient ou définit le texte brut d'un TextFrame.<br/>            Lecture/écriture **str**. |
| [`text_frame_format`](/slides/python-net/fr/aspose.slides/textframe/text_frame_format/) | Renvoie l'objet de mise en forme pour cet objet TextFrame.<br/>            Lecture seule [`ITextFrameFormat`](/slides/python-net/fr/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/textframe/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/fr/aspose.slides/textframe/slide/) | Renvoie la diapositive parente d'un TextFrame.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/textframe/presentation/) | Renvoie la présentation parente d'un TextFrame.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/fr/aspose.slides/textframe/parent_shape/) | Renvoie la forme parente ou None si l'objet parent n'implémente pas l'interface IShape<br/>            Lecture seule [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fr/aspose.slides/textframe/parent_cell/) | Renvoie la cellule parente ou None si l'objet parent n'implémente pas l'interface ICell.<br/>            Lecture seule [`ICell`](/slides/python-net/fr/aspose.slides/icell). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fr/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fr/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fr/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fr/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fr/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/textframe/join_portions_with_same_formatting/#) | Fusionne les enchaînements avec la même mise en forme dans tous les paragraphes. |
| [`split_text_by_columns(self)`](/slides/python-net/fr/aspose.slides/textframe/split_text_by_columns/#) | Divise le contenu texte du [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe) en un tableau de chaînes,  <br/>            où chaque élément correspond à une colonne texte distincte à l'intérieur du cadre. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fr/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fr/aspose.slides/textframe/replace_regex/#str-str) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
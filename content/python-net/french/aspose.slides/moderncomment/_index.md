---
title: ModernComment class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/moderncomment/
---
## ModernComment classe

Représente un commentaire sur une diapositive.

**Héritage:**[`ModernComment`](/slides/python-net/fr/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/fr/aspose.slides/comment)

Le type ModernComment expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`text`](/slides/python-net/fr/aspose.slides/moderncomment/text/) | Renvoie ou définit le texte brut d'un commentaire de diapositive.<br/>            Lecture/écriture **str**. |
| [`created_time`](/slides/python-net/fr/aspose.slides/moderncomment/created_time/) | Renvoie ou définit l'heure de création d'un commentaire.<br/>            Définir cette propriété sur **System.DateTime** signifie qu'aucune heure de commentaire n'est définie.<br/>            Lecture/écriture **System.DateTime**. |
| [`slide`](/slides/python-net/fr/aspose.slides/moderncomment/slide/) | Renvoie ou définit la diapositive parente d'un commentaire.<br/>            Lecture seule [`ISlide`](/slides/python-net/fr/aspose.slides/islide). |
| [`author`](/slides/python-net/fr/aspose.slides/moderncomment/author/) | Renvoie l'auteur d'un commentaire.<br/>            Lecture seule [`ICommentAuthor`](/slides/python-net/fr/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/fr/aspose.slides/moderncomment/position/) | Renvoie ou définit la position d'un commentaire sur une diapositive.<br/>            Lecture/écriture **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/fr/aspose.slides/moderncomment/parent_comment/) | Renvoie ou définit le commentaire parent.<br/>            Lecture/écriture [`IComment`](/slides/python-net/fr/aspose.slides/icomment). |
| [`shape`](/slides/python-net/fr/aspose.slides/moderncomment/shape/) | Renvoie une forme associée au commentaire.<br/>            Lecture seule [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/fr/aspose.slides/moderncomment/text_selection_start/) | Renvoie ou définit la position de départ de la sélection de texte dans le cadre de texte si le commentaire est associé à une AutoShape.<br/>            Lecture/écriture **int**. |
| [`text_selection_length`](/slides/python-net/fr/aspose.slides/moderncomment/text_selection_length/) | Renvoie ou définit la longueur de la sélection de texte dans le cadre de texte si le commentaire est associé à une AutoShape.<br/>            Lecture/écriture **int**. |
| [`status`](/slides/python-net/fr/aspose.slides/moderncomment/status/) | Renvoie ou définit l'état du commentaire.<br/>            Lecture/écriture [`ModernCommentStatus`](/slides/python-net/fr/aspose.slides/moderncommentstatus). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides/moderncomment/remove/#) | Supprime le commentaire et toutes ses réponses de la collection parente. |


### Voir aussi
* classe [`Comment`](/slides/python-net/fr/aspose.slides/comment)
* classe [`ModernComment`](/slides/python-net/fr/aspose.slides/moderncomment)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
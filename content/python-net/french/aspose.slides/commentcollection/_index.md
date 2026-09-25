---
title: CommentCollection class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/commentcollection/
---
## CommentCollection classe

Représente une collection de commentaires d'un auteur.

Le type CommentCollection expose les membres suivants :

Obtient l'élément à l'index spécifié.  
            Lecture seule [`Comment`](/slides/python-net/fr/aspose.slides/comment).

## Accesseur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/commentcollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/fr/aspose.slides/commentcollection/to_array/#) | Crée et renvoie un tableau contenant tous les commentaires. |
| [`to_array(self, start_index, count)`](/slides/python-net/fr/aspose.slides/commentcollection/to_array/#int-int) | Crée et renvoie un tableau contenant tous les commentaires de la plage spécifiée. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/fr/aspose.slides/commentcollection/add_comment/#str-islide-asposeslidespointf-datetime) | Ajoute un nouveau commentaire à la fin d'une collection. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/fr/aspose.slides/commentcollection/add_modern_comment/#str-islide-ishape-asposeslidespointf-datetime) | Ajoute un nouveau commentaire moderne à la fin d'une collection. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/fr/aspose.slides/commentcollection/insert_comment/#int-str-islide-asposeslidespointf-datetime) | Insère un nouveau commentaire dans une collection à l'index spécifié. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/fr/aspose.slides/commentcollection/insert_modern_comment/#int-str-islide-ishape-asposeslidespointf-datetime) | Insère un nouveau commentaire moderne dans une collection à l'index spécifié. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/commentcollection/remove_at/#int) | Supprime l'élément à l'index spécifié dans une collection. |
| [`remove(self, comment)`](/slides/python-net/fr/aspose.slides/commentcollection/remove/#icomment) | Supprime la première occurrence du commentaire spécifié dans une collection. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides/commentcollection/clear/#) | Supprime tous les commentaires d'une collection. |
| [`find_comment_by_idx(self, idx)`](/slides/python-net/fr/aspose.slides/commentcollection/find_comment_by_idx/#int) | Recherche un commentaire dans la collection par index. |


### Voir aussi
* classe [`Comment`](/slides/python-net/fr/aspose.slides/comment)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
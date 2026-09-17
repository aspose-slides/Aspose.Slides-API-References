---
title: ICommentCollection class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/icommentcollection/
---
## ICommentCollection classe

Représente une collection de commentaires d'un auteur.

Le type ICommentCollection expose les membres suivants :

Obtient l'élément à l'index spécifié.  
            Lecture seule [`IComment`](/slides/python-net/fr/aspose.slides/icomment).

## Accesseur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/icommentcollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/fr/aspose.slides/icommentcollection/to_array/#) | Crée et renvoie un tableau contenant tous les commentaires. |
| [`to_array(self, start_index, count)`](/slides/python-net/fr/aspose.slides/icommentcollection/to_array/#int-int) | Crée et renvoie un tableau contenant tous les commentaires de la plage spécifiée. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/fr/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Ajoute un nouveau commentaire à la fin d'une collection. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/fr/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Ajoute un nouveau commentaire moderne à la fin d'une collection. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/fr/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Insère un nouveau commentaire dans une collection à l'index spécifié. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/fr/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Insère un nouveau commentaire moderne dans une collection à l'index spécifié. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/icommentcollection/remove_at/#int) | Supprime l'élément à l'index spécifié dans une collection. |
| [`remove(self, comment)`](/slides/python-net/fr/aspose.slides/icommentcollection/remove/#icomment) | Supprime la première occurrence du commentaire spécifié dans une collection. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides/icommentcollection/clear/#) | Supprime tous les commentaires d'une collection. |


### Voir aussi
* classe [`IComment`](/slides/python-net/fr/aspose.slides/icomment)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
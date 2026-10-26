---
title: Video class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/video/
---
## Video classe

Représente une image intégrée dans une présentation.

Le type Video expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`content_type`](/slides/python-net/fr/aspose.slides/video/content_type/) | Renvoie un type MIME d'une vidéo, encodé en [`Video.binary_data`](/slides/python-net/fr/aspose.slides/video/binary_data).<br/>            Lecture seule **str**. |
| [`binary_data`](/slides/python-net/fr/aspose.slides/video/binary_data/) | Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la <br/>            méthode [`Video.get_stream`](/slides/python-net/fr/aspose.slides/video/get_stream) pour éviter le chargement inutile des données de la vidéo en mémoire <br/>            ou même une OutOfMemoryException.<br/>            Lecture seule **int**[]. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/fr/aspose.slides/video/get_stream/#) | Renvoie le flux Stream pour la lecture.<br/>            Utilisez 'using' ou fermez le flux après utilisation. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
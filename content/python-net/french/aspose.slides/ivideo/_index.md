---
title: IVideo class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ivideo/
---
## IVideo classe

Représente une vidéo intégrée dans une présentation.

Le type IVideo expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`content_type`](/slides/python-net/fr/aspose.slides/ivideo/content_type/) | Renvoie un type MIME d'une vidéo, encodé en [`IVideo.binary_data`](/slides/python-net/fr/aspose.slides/ivideo/binary_data).<br/>            Lecture seule **str**. |
| [`binary_data`](/slides/python-net/fr/aspose.slides/ivideo/binary_data/) | Renvoie une copie des données audio. En cas de grande quantité de données, envisagez d'utiliser la <br/>            méthode [`IVideo.get_stream`](/slides/python-net/fr/aspose.slides/ivideo/get_stream) pour éviter le chargement inutile des données vidéo en mémoire <br/>            ou même une OutOfMemoryException.<br/>            Lecture seule **int**[]. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/fr/aspose.slides/ivideo/get_stream/#) | Renvoie un flux Stream pour la lecture.<br/>            Utilisez 'using' ou fermez le flux après utilisation. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
---
title: Audio class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/audio/
---
## Audio classe

Représente un fichier audio intégré.

Le type Audio expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`content_type`](/slides/python-net/fr/aspose.slides/audio/content_type/) | Renvoie un type MIME d'un audio, encodé en [`Audio.binary_data`](/slides/python-net/fr/aspose.slides/audio/binary_data).<br/>            Lecture seule **str**. |
| [`binary_data`](/slides/python-net/fr/aspose.slides/audio/binary_data/) | Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez <br/>            d'utiliser la méthode [`Audio.get_stream`](/slides/python-net/fr/aspose.slides/audio/get_stream) pour éviter le chargement inutile des données d'un audio<br/>            en mémoire ou même une OutOfMemoryException.<br/>            Lecture seule **int**[]. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/fr/aspose.slides/audio/get_stream/#) | Renvoie Stream stream pour la lecture.<br/>            Utilisez 'using' ou fermez le stream après utilisation. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
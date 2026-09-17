---
title: IAudio class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iaudio/
---
## IAudio classe

Représente un fichier audio intégré.

Le type IAudio expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/fr/aspose.slides/iaudio/content_type/) | Renvoie le type MIME d'un audio, encodé en [`IAudio.binary_data`](/slides/python-net/fr/aspose.slides/iaudio/binary_data).<br/>            Lecture seule **str**. |
| [`binary_data`](/slides/python-net/fr/aspose.slides/iaudio/binary_data/) | Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez <br/>            d'utiliser la méthode [`IAudio.get_stream`](/slides/python-net/fr/aspose.slides/iaudio/get_stream) pour éviter le chargement inutile des données de l'audio<br/>            en mémoire ou même une OutOfMemoryException.<br/>            Lecture seule **int**[]. |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/fr/aspose.slides/iaudio/get_stream/#) | Renvoie Stream stream pour la lecture.<br/>            Utilisez 'using' ou fermez le stream après utilisation. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
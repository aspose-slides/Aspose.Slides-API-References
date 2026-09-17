---
title: VbaProject class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.vba/vbaproject/
---
## VbaProject classe

Représente un projet VBA avec des macros de présentation.

Le type VbaProject expose les membres suivants :

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.vba/vbaproject/__init__/#) | Ce constructeur crée un nouveau projet VBA à partir de zéro.<br/>            Le projet sera créé avec la page de code 1252 Windows Latin 1 (ANSI) |
| [`__init__(self, data)`](/slides/python-net/fr/aspose.slides.vba/vbaproject/__init__/#bytes) | Ce constructeur charge le projet VBA à partir de la représentation binaire d'un conteneur OLE. |

## Propriétés

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/fr/aspose.slides.vba/vbaproject/name/) | Renvoie le nom du projet VBA.<br/>            Lecture-seule **str**. |
| [`modules`](/slides/python-net/fr/aspose.slides.vba/vbaproject/modules/) | Renvoie la liste de tous les modules contenus dans le projet VBA.<br/>            Lecture-seule [`IVbaModuleCollection`](/slides/python-net/fr/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/fr/aspose.slides.vba/vbaproject/references/) | Renvoie la liste de toutes les références contenues dans le projet VBA.<br/>            Lecture-seule [`IVbaReferenceCollection`](/slides/python-net/fr/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/fr/aspose.slides.vba/vbaproject/is_password_protected/) | Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet.<br/>            Lecture-seule **bool**. |

## Méthodes

| Method | Description |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/fr/aspose.slides.vba/vbaproject/to_binary/#) | Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE |


### Voir aussi
* module [`aspose.slides.vba`](/slides/python-net/fr/aspose.slides.vba)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
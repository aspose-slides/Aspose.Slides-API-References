---
title: Portion class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/portion/
---
## Portion classe

Represents a portion of text inside a text paragraph.

The Portion type exposes the following members:

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/portion/__init__/#) | Initialise une nouvelle instance de la classe Portion. |
| [`__init__(self, str)`](/slides/python-net/fr/aspose.slides/portion/__init__/#str) | Initialise une nouvelle instance de la classe Portion. |
| [`__init__(self, portion)`](/slides/python-net/fr/aspose.slides/portion/__init__/#portion) | Initialise une nouvelle instance de la classe Portion. |

## Propriétés

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/fr/aspose.slides/portion/portion_format/) | Renvoie l'objet de mise en forme qui contient les propriétés de mise en forme définies explicitement de la portion de texte sans héritage appliqué.<br/>            Lecture seule [`IPortionFormat`](/slides/python-net/fr/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/fr/aspose.slides/portion/text/) | Obtient ou définit le texte brut d'une portion.<br/>            Lecture/écriture **str**. |
| [`field`](/slides/python-net/fr/aspose.slides/portion/field/) | Renvoie un champ de cette portion.<br/>            Lecture seule [`IField`](/slides/python-net/fr/aspose.slides/ifield). |
| [`slide`](/slides/python-net/fr/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/portion/presentation/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/fr/aspose.slides/portion/add_field/#ifieldtype) | Convertit cette portion en champ mis à jour automatiquement. |
| [`add_field(self, internal_string)`](/slides/python-net/fr/aspose.slides/portion/add_field/#str) | Convertit cette portion en champ mis à jour automatiquement. |
| [`remove_field(self)`](/slides/python-net/fr/aspose.slides/portion/remove_field/#) | Convertit cette portion de champ en portion simple. |
| [`get_rect(self)`](/slides/python-net/fr/aspose.slides/portion/get_rect/#) | Obtient les coordonnées du rectangle qui englobe la portion. Le rectangle comprend toutes les lignes de<br/>             texte dans la portion, y compris les lignes vides. |
| [`get_coordinates(self)`](/slides/python-net/fr/aspose.slides/portion/get_coordinates/#) | Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion à partir du premier caractère en incluant le bord latéral gauche. La coordonnée Y inclut le bord supérieur. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
---
title: IPortion class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iportion/
---
## IPortion classe

Représente une portion de texte à l'intérieur d'un paragraphe de texte.

Le type IPortion expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/fr/aspose.slides/iportion/portion_format/) | Renvoie l'objet de formatage qui contient les propriétés de formatage explicitement définies de la portion de texte sans aucune héritage appliquée.<br/>            Lecture seule [`IPortionFormat`](/slides/python-net/fr/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/fr/aspose.slides/iportion/text/) | Obtient ou définit le texte brut d'une portion.<br/>            Lecture/écriture **str**. |
| [`field`](/slides/python-net/fr/aspose.slides/iportion/field/) | Renvoie un champ de cette portion.<br/>            Lecture seule [`IField`](/slides/python-net/fr/aspose.slides/ifield). |
| [`slide`](/slides/python-net/fr/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/iportion/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/fr/aspose.slides/iportion/add_field/#ifieldtype) | Convertit cette portion en champ mis à jour automatiquement. |
| [`add_field(self, internal_string)`](/slides/python-net/fr/aspose.slides/iportion/add_field/#str) | Convertit cette portion en champ mis à jour automatiquement. |
| [`remove_field(self)`](/slides/python-net/fr/aspose.slides/iportion/remove_field/#) | Convertit cette portion de champ en portion simple. |
| [`get_rect(self)`](/slides/python-net/fr/aspose.slides/iportion/get_rect/#) | Obtient les coordonnées du rectangle qui délimite la portion. Le rectangle comprend toutes les lignes de<br/>             texte dans la portion, y compris les lignes vides. |
| [`get_coordinates(self)`](/slides/python-net/fr/aspose.slides/iportion/get_coordinates/#) | Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion à partir du premier caractère, incluant la bordure gauche. La coordonnée Y inclut la bordure supérieure. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
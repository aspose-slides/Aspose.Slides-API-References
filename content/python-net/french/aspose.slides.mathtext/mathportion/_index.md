---
title: MathPortion class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathportion/
---
## MathPortion classe

Représente une portion avec un contexte mathématique.

**Héritage:**[`MathPortion`](/slides/python-net/fr/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/fr/aspose.slides/portion)

Le type MathPortion expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/__init__/#) | Initialise une nouvelle instance de la classe MathPortion. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/portion_format/) | Renvoie l'objet de mise en forme qui contient les propriétés de mise en forme explicitement définies de la portion de texte sans héritage appliqué.<br/>            Lecture seule [`IPortionFormat`](/slides/python-net/fr/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/text/) | Obtient ou définit le texte brut d'une portion.<br/>            Lecture/écriture **str**. |
| [`field`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/field/) | Renvoie un champ de cette portion.<br/>            Lecture seule [`IField`](/slides/python-net/fr/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/math_paragraph/) | Paragraphe mathématique |
| [`slide`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | Convertit cette portion en champ automatiquement mis à jour. |
| [`add_field(self, internal_string)`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/add_field/#str) | Convertit cette portion en champ automatiquement mis à jour. |
| [`remove_field(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/remove_field/#) | Convertit cette portion de champ en portion simple. |
| [`get_rect(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/get_rect/#) | Obtient les coordonnées du rectangle qui encadre la portion. Le rectangle inclut toutes les lignes de<br/>             texte dans la portion, y compris les lignes vides. |
| [`get_coordinates(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/get_coordinates/#) | Obtient les coordonnées du début de la portion. La coordonnée X du point représente le début de la portion à partir du premier caractère, y compris la bordure latérale gauche. La coordonnée Y inclut la bordure supérieure. |

### Voir aussi
* classe [`MathPortion`](/slides/python-net/fr/aspose.slides.mathtext/mathportion)
* classe [`Portion`](/slides/python-net/fr/aspose.slides/portion)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
---
title: ISectionCollection class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/isectioncollection/
---
## ISectionCollection classe

Représente une collection de sections.

Le type ISectionCollection expose les membres suivants :

Obtient l'élément à l'index spécifié.
            Lecture seule [`ISection`](/slides/python-net/fr/aspose.slides/isection).

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/isectioncollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/fr/aspose.slides/isectioncollection/add_section/#str-islide) | Ajoute une nouvelle section démarrée à partir d'une diapositive spécifique. |
| [`add_empty_section(self, name, index)`](/slides/python-net/fr/aspose.slides/isectioncollection/add_empty_section/#str-int) | Ajoute une section vide à la position spécifiée de la collection. |
| [`remove_section_with_slides(self, section)`](/slides/python-net/fr/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | Supprime la section et les diapositives qu'elle contient. |
| [`remove_section(self, section)`](/slides/python-net/fr/aspose.slides/isectioncollection/remove_section/#isection) | Supprime la section. Les diapositives contenues dans la section seront fusionnées dans la section précédente. |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/fr/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | Déplace la section et ses diapositives de la collection vers la position spécifiée. |
| [`append_empty_section(self, name)`](/slides/python-net/fr/aspose.slides/isectioncollection/append_empty_section/#str) | Ajoute une section vide à la fin de la collection. |
| [`index_of(self, section)`](/slides/python-net/fr/aspose.slides/isectioncollection/index_of/#isection) | Renvoie l'index de la section spécifiée dans la collection. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides/isectioncollection/clear/#) | Supprime toutes les sections de la collection. |


### Voir aussi
* classe [`ISection`](/slides/python-net/fr/aspose.slides/isection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
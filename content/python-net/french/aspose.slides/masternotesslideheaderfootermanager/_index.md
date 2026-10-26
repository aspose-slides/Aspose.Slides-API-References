---
title: MasterNotesSlideHeaderFooterManager class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager classe

Représente le gestionnaire qui maintient le comportement du pied de page, de la date-heure, des espaces réservés de numéro de page de la diapositive de notes maîtresse et de tous les espaces réservés enfants.
            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.
            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse.

**Inheritance:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/fr/aspose.slides/baseheaderfootermanager)

Le type MasterNotesSlideHeaderFooterManager expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | Obtient la valeur indiquant qu'un espace réservé de pied de page est présent.<br/>            Lecture **bool**. |
| [`is_slide_number_visible`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | Obtient la valeur indiquant qu'un espace réservé du numéro de page est présent.<br/>            Lecture**bool**. |
| [`is_date_time_visible`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | Obtient la valeur indiquant qu'un espace réservé de date-heure est présent.<br/>            Lecture**bool**. |
| [`is_header_visible`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | Obtient la valeur indiquant qu'un espace réservé d'en-tête est présent.<br/>            Lecture **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | Modifie la visibilité de l'espace réservé du pied de page de la diapositive. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | Modifie la visibilité de l'espace réservé du numéro de page de la diapositive. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | Modifie la visibilité de l'espace réservé de date-heure de la diapositive. |
| [`set_footer_text(self, text)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | Définit le texte de l'espace réservé du pied de page de la diapositive. |
| [`set_date_time_text(self, text)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | Définit le texte de l'espace réservé de date-heure de la diapositive. |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | Modifie la visibilité de l'espace réservé d'en-tête de la diapositive. |
| [`set_header_text(self, text)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | Définit le texte de l'espace réservé d'en-tête de la diapositive. |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | Modifie la visibilité de l'espace réservé d'en-tête de la diapositive de notes maîtresse et de tous les espaces réservés d'en-tête enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | Définit le texte de l'espace réservé d'en-tête de la diapositive de notes maîtresse et de tous les espaces réservés d'en-tête enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | Modifie la visibilité de l'espace réservé du pied de page de la diapositive maîtresse et de tous les espaces réservés de pied de page enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | Modifie la visibilité de l'espace réservé du numéro de page de la diapositive maîtresse et de tous les espaces réservés de numéro de page enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | Modifie la visibilité de l'espace réservé de date-heure de la diapositive maîtresse et de tous les espaces réservés de date-heure enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | Définit le texte de l'espace réservé du pied de page de la diapositive maîtresse et de tous les espaces réservés de pied de page enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | Définit le texte de l'espace réservé de date-heure de la diapositive maîtresse et de tous les espaces réservés de date-heure enfants.<br/>            Les espaces réservés enfants désignent les espaces réservés contenus sur les diapositives de notes dépendantes.<br/>            Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |


### Voir aussi
* classe [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/basehandoutnotesslideheaderfootermanager)
* classe [`BaseHeaderFooterManager`](/slides/python-net/fr/aspose.slides/baseheaderfootermanager)
* classe [`BaseSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/baseslideheaderfootermanager)
* classe [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/masternotesslideheaderfootermanager)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
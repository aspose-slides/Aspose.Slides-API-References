---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection classe

Représente une collection de toutes les diapositives de mise en page dans la présentation.  
Extends LayoutSlideCollection class with methods for adding/cloning  
layout slides in context of uniting of the individual collections of master's layout slides.

**Héritage:**[`GlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/fr/aspose.slides/layoutslidecollection)

Le type GlobalLayoutSlideCollection expose les membres suivants :

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Ajoute une copie d'une diapositive de mise en page spécifiée à la présentation. |
| [`get_by_type(self, type)`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Renvoie la première diapositive de mise en page du type spécifié.<br/>            Un type de diapositive de mise en page à rechercher.[`LayoutSlide`](/slides/python-net/fr/aspose.slides/layoutslide) avec le type spécifié ou None si aucune mise en page n'est trouvée. |
| [`remove(self, value)`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Supprime une mise en page de la collection. |
| [`remove_unused(self)`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/remove_unused/#) | Supprime les diapositives de mise en page inutilisées (diapositives de mise en page dont HasDependingSlides est false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Ajoute une nouvelle diapositive de mise en page à la présentation. |


### Voir aussi
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection)
* classe [`LayoutSlideCollection`](/slides/python-net/fr/aspose.slides/layoutslidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
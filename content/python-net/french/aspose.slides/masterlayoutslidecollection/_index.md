---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection classe

Représente une collection de toutes les diapositives de mise en page du maître défini.
            Étend la classe LayoutSlideCollection avec des méthodes pour ajouter/insérer/supprimer/dupliquer/reordonner les diapositives de mise en page dans le contexte des collections individuelles des diapositives de mise en page du maître.

**Héritage:**[`MasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/fr/aspose.slides/layoutslidecollection)

Le type MasterLayoutSlideCollection expose les membres suivants :

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Renvoie la première diapositive de mise en page du type spécifié.<br/>            Un type de diapositive de mise en page à rechercher.[`LayoutSlide`](/slides/python-net/fr/aspose.slides/layoutslide) avec le type spécifié ou None si aucune mise en page n'est trouvée. |
| [`remove(self, value)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Supprime une mise en page de la collection. |
| [`remove_unused(self)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Supprime les diapositives de mise en page inutilisées (diapositives de mise en page dont HasDependingSlides est false). |
| [`add_clone(self, source_layout)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Ajoute une copie d'une diapositive de mise en page spécifiée à la fin de la collection. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Insère une copie d'une diapositive de mise en page spécifiée à la position indiquée de la collection. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Ajoute une nouvelle diapositive de mise en page à la fin de la collection. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Insère une nouvelle diapositive de mise en page à la position indiquée de la collection. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Supprime l'élément à l'index spécifié de la collection. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Déplace la diapositive de mise en page de la collection vers la position spécifiée. |

### Voir aussi
* classe [`LayoutSlideCollection`](/slides/python-net/fr/aspose.slides/layoutslidecollection)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
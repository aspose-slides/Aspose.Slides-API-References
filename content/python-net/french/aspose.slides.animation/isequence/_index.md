---
title: ISequence class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.animation/isequence/
---
## ISequence classe

Représente une séquence (collection d'effets).

Le type ISequence expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/fr/aspose.slides.animation/isequence/count/) | Renvoie le nombre d'effets dans une séquence.<br/>            Lecture seule **int**. |
| [`trigger_shape`](/slides/python-net/fr/aspose.slides.animation/isequence/trigger_shape/) | Renvoie ou définit la cible de forme pour la séquence INTERACTIVE.<br/>            Si la séquence n'est pas interactive, renvoie None.<br/>            Lecture/écriture [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |

Renvoie un effet à l'index spécifié.

## Indexeur

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.animation/isequence/__getitem__/) | Index |

## Méthodes

| Method | Description |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/fr/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Ajoute un nouvel effet à la fin de la séquence. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/fr/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/fr/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Ajoute le nouvel effet d'animation de diagramme pour la catégorie ou la série à la fin de la séquence. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/fr/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Ajoute le nouvel effet d'animation de diagramme pour les éléments de la catégorie ou de la série à la fin de la séquence. |
| [`remove(self, item)`](/slides/python-net/fr/aspose.slides.animation/isequence/remove/#ieffect) | Supprime l'effet spécifié d'une collection. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides.animation/isequence/remove_at/#int) | Supprime un effet d'une collection. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides.animation/isequence/clear/#) | Supprime tous les effets d'une collection. |
| [`remove_by_shape(self, shape)`](/slides/python-net/fr/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Supprime l'effet pour la forme spécifiée. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/fr/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Renvoie un tableau d'effets pour la forme spécifiée. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/fr/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Renvoie un tableau d'effets pour le paragraphe spécifié. |
| [`get_count(self, shape)`](/slides/python-net/fr/aspose.slides.animation/isequence/get_count/#ishape) | Renvoie le nombre d'effets pour la forme spécifiée. |

### Voir aussi
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
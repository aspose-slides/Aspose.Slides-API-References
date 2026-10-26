---
title: IFontFallBackRule class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ifontfallbackrule/
---
## IFontFallBackRule classe

Représente la règle de secours de police

Le type IFontFallBackRule expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/range_start_index/) | Obtient le premier indice de la plage unicode continue. |
| [`range_end_index`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/range_end_index/) | Obtient le dernier indice de la plage unicode continue. |
| [`count`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/count/) | Obtient le nombre de polices réellement définies pour la plage. |

Obtient le nom de la police à l'indice spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#str) | Ajoute une nouvelle police(s) à la liste des polices FallBack. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#liststr) | Ajoute de nouvelles polices à la liste des polices FallBack. |
| [`to_array(self)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/to_array/#) | Crée et renvoie un tableau contenant toutes les polices FallBack pour cette règle. |
| [`to_array(self, start_index, count)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/to_array/#int-int) | Crée et renvoie un tableau contenant toutes les polices FallBack de la plage spécifiée dans la liste. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/clear/#) | Supprime toutes les polices de la liste. |
| [`remove(self, font_name)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/remove/#str) | Supprime la première occurrence d'une police FallBack spécifique de la liste. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/remove_at/#int) | Supprime la police FallBack à l'indice spécifié de la liste. |
| [`index_of(self, font_name)`](/slides/python-net/fr/aspose.slides/ifontfallbackrule/index_of/#str) | Renvoie un indice de la règle spécifiée dans la collection. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
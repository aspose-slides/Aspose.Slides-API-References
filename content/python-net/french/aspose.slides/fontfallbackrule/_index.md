---
title: FontFallBackRule class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/fontfallbackrule/
---
## FontFallBackRule classe

Représente la règle de secours de police

Le type FontFallBackRule expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Crée une nouvelle instance. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Crée une nouvelle instance. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/fr/aspose.slides/fontfallbackrule/range_start_index/) | Obtient le premier indice de la plage unicode continue. |
| [`range_end_index`](/slides/python-net/fr/aspose.slides/fontfallbackrule/range_end_index/) | Obtient le dernier indice de la plage unicode continue. |
| [`count`](/slides/python-net/fr/aspose.slides/fontfallbackrule/count/) | Obtient le nombre de polices réellement définies pour la plage.<br/>            Lecture-seule **int**. |

Obtient le nom de police à l'indice spécifié.  
            Lecture-seule [`IFontFallBackRule`](/slides/python-net/fr/aspose.slides/ifontfallbackrule).

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Ajoute une ou plusieurs nouvelles polices à la liste des polices de secours. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Ajoute de nouvelles polices à la liste des polices de secours. |
| [`to_array(self)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/to_array/#) | Crée et renvoie un tableau contenant toutes les polices de secours pour cette règle. |
| [`to_array(self, start_index, count)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/to_array/#int-int) | Crée et renvoie un tableau contenant toutes les polices de secours de la plage spécifiée dans la liste. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/clear/#) | Supprime toutes les polices de la liste. |
| [`remove(self, font_name)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/remove/#str) | Supprime la première occurrence d'une police de secours spécifique de la liste. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/remove_at/#int) | Supprime la police de secours à l'indice spécifié de la liste. |
| [`index_of(self, font_name)`](/slides/python-net/fr/aspose.slides/fontfallbackrule/index_of/#str) | Renvoie l'indice de la règle spécifiée dans la collection. |

### Voir aussi
* classe [`IFontFallBackRule`](/slides/python-net/fr/aspose.slides/ifontfallbackrule)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
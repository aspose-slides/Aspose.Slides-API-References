---
title: IDataLabel class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabel/
---
## IDataLabel classe

Représente les étiquettes d’une série.

Le type IDataLabel expose les membres suivants :

## Propriété

| Propriété | Description |
| :- | :- |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/idatalabel/is_visible/) | False signifie que l’étiquette de données n’est pas visible (et donc tous les indicateurs Show*-flags (ShowValue, ...) sont faux).<br/>            Lecture seule **bool**. |
| [`data_label_format`](/slides/python-net/fr/aspose.slides.charts/idatalabel/data_label_format/) | Renvoie le format de l’étiquette de données.<br/>            Lecture seule [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/fr/aspose.slides.charts/idatalabel/value_from_cell/) | Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie. |
| [`x`](/slides/python-net/fr/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/fr/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/fr/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/fr/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/fr/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/fr/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/fr/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/idatalabel/actual_height/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fr/aspose.slides.charts/idatalabel/hide/#) | Masque l’étiquette de données en réglant tous les indicateurs Show*-flags (ShowValue, ...) sur l’état faux.<br/>            IsVisible sera false après cela. |
| [`get_actual_label_text(self)`](/slides/python-net/fr/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Renvoie le texte réel de l’étiquette basé sur les paramètres DataLabelFormat ou la valeur TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fr/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
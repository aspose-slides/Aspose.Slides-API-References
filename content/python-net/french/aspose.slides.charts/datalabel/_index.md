---
title: DataLabel class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/datalabel/
---
## DataLabel classe

Représente les libellés d'une série.

Le type DataLabel expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/fr/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Crée une nouvelle instance de DataLabel classe. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/datalabel/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/datalabel/is_visible/) | False signifie que le libellé de données n'est pas visible (et donc que tous les indicateurs Show*-flags (ShowValue, ...) sont false).<br/>            Lecture seule **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/fr/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Peut contenir un texte riche formaté. Si cette propriété n'est pas None, alors cette <br/>            valeur de texte formaté remplace le texte auto-généré du libellé de données.<br/>            Le texte auto-généré du libellé de données désigne le texte géré par les propriétés ShowSeriesName, <br/>            ShowValue, ... et formaté avec la propriété TextFormatManager.TextFormat.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/datalabel/text_format/) | Renvoie le format du texte.<br/>            Lecture seule [`IChartTextFormat`](/slides/python-net/fr/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/fr/aspose.slides.charts/datalabel/x/) | Renvoie ou définit la coordonnée x d'un titre comme une fraction de la largeur du graphique.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides.charts/datalabel/y/) | Renvoie ou définit la coordonnée y d'un titre comme une fraction de la hauteur du graphique.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides.charts/datalabel/width/) | Renvoie ou définit la largeur d'un titre comme une fraction de la largeur du graphique.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides.charts/datalabel/height/) | Renvoie ou définit la hauteur d'un titre comme une fraction de la hauteur du graphique.<br/>            Lecture/écriture **float**. |
| [`right`](/slides/python-net/fr/aspose.slides.charts/datalabel/right/) | Droite.<br/>            Lecture seule **float**. |
| [`bottom`](/slides/python-net/fr/aspose.slides.charts/datalabel/bottom/) | Bas.<br/>            Lecture seule **float**. |
| [`data_label_format`](/slides/python-net/fr/aspose.slides.charts/datalabel/data_label_format/) | Renvoie le format du libellé de données.<br/>            Lecture seule [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/fr/aspose.slides.charts/datalabel/value_from_cell/) | Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est égale à true. |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/datalabel/actual_x/) | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/datalabel/actual_y/) | Spécifie le sommet réel de l'élément du graphique par rapport au coin supérieur gauche du graphique.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/datalabel/actual_width/) | Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/datalabel/actual_height/) | Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/datalabel/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fr/aspose.slides.charts/datalabel/hide/#) | Masque le libellé de données en réglant tous les indicateurs Show*-flags (ShowValue, ...) sur l'état false.<br/>            IsVisible sera false après cela. |
| [`get_actual_label_text(self)`](/slides/python-net/fr/aspose.slides.charts/datalabel/get_actual_label_text/#) | Renvoie le texte réel du libellé basé sur les paramètres DataLabelFormat ou la valeur TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fr/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Initialise TextFrameForOverriding avec le texte du paramètre "text".<br/>            Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
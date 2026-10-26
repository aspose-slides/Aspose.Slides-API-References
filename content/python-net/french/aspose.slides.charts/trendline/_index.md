---
title: Trendline class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/trendline/
---
## Classe Trendline

La classe représente la ligne de tendance d’une série de graphique

Le type Trendline expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/fr/aspose.slides.charts/trendline/trendline_name/) | Obtient ou définit le nom de la ligne de tendance.<br/>            Lecture/écriture **str**. |
| [`trendline_type`](/slides/python-net/fr/aspose.slides.charts/trendline/trendline_type/) | Obtient ou définit le type de ligne de tendance.<br/>            Lecture/écriture [`TrendlineType`](/slides/python-net/fr/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/fr/aspose.slides.charts/trendline/format/) | Représente le format de la ligne de tendance.<br/>            Lecture/écriture [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/fr/aspose.slides.charts/trendline/backward/) | Spécifie le nombre de catégories (ou d’unités sur un graphique de dispersion) que la ligne de tendance étend avant<br/>            les données de la série concernée. Sur les graphiques de dispersion et non-dispersion, la valeur doit être toute valeur non négative.<br/>            Lecture/écriture **float**. |
| [`forward`](/slides/python-net/fr/aspose.slides.charts/trendline/forward/) | Spécifie le nombre de catégories (ou d’unités sur un graphique de dispersion) que la ligne de tendance étend après les<br/>            données de la série concernée. Sur les graphiques de dispersion et non-dispersion, la valeur doit être toute valeur non négative.<br/>            Lecture/écriture **float**. |
| [`intercept`](/slides/python-net/fr/aspose.slides.charts/trendline/intercept/) | Spécifie la valeur où la ligne de tendance doit croiser l’axe des y. Cette propriété n’est prise en charge que<br/>            lorsque le type de ligne de tendance est exp, linear ou poly.<br/>            Lecture/écriture **float**. |
| [`display_equation`](/slides/python-net/fr/aspose.slides.charts/trendline/display_equation/) | Indique que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur R-squared).<br/>            Lecture/écriture **bool**. |
| [`order`](/slides/python-net/fr/aspose.slides.charts/trendline/order/) | Indique l’ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6.<br/>            Lecture/écriture **int**. |
| [`period`](/slides/python-net/fr/aspose.slides.charts/trendline/period/) | Indique la période de la ligne de tendance pour une ligne de tendance moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255.<br/>            Lecture/écriture **int**. |
| [`display_r_squared_value`](/slides/python-net/fr/aspose.slides.charts/trendline/display_r_squared_value/) | Indique que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation).<br/>            Lecture/écriture **bool**. |
| [`related_legend_entry`](/slides/python-net/fr/aspose.slides.charts/trendline/related_legend_entry/) | Représente l’entrée de légende liée à cette ligne de tendance<br/>            Lecture seule [`ILegendEntryProperties`](/slides/python-net/fr/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/fr/aspose.slides.charts/trendline/text_frame_for_overriding/) | Peut contenir un texte riche formaté. Si cette propriété n’est pas None, alors cette valeur de texte formaté remplace le texte généré automatiquement de l’étiquette de données.<br/>            Le texte généré automatiquement de l’étiquette de données désigne le texte géré par les propriétés ShowSeriesName, <br/>            ShowValue, … et formaté avec la propriété TextFormatManager.TextFormat.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/trendline/text_format/) | Retourne le format du texte.<br/>            Lecture seule [`IChartTextFormat`](/slides/python-net/fr/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/trendline/chart/) | Retourne le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/trendline/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fr/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Initialise TextFrameForOverriding avec le texte du paramètre "text".<br/>            Si TextFrameForOverriding est déjà initialisé, alors modifie simplement son texte. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
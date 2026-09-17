---
title: ErrorBarsFormat class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/errorbarsformat/
---
## classe ErrorBarsFormat

Représente les barres d’erreur des séries de graphique. Les valeurs personnalisées d’ErrorBars se trouvent dans IChartDataPointCollection (dans la propriété [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Le type ErrorBarsFormat expose les membres suivants :

## Propriété

| Propriété | Description |
| :- | :- |
| [`type`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/type/) | Obtient ou définit le type des barres d’erreur. <br/>            Lecture/écriture [`ErrorBarType`](/slides/python-net/fr/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/value_type/) | Représente les méthodes possibles pour déterminer la longueur des barres d’erreur. <br/>            Dans le cas d’un type de valeur personnalisé, utilisez la propriété [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) du point de données spécifique dans la collection DataPoints de la série.<br/>            Dans le cas des types de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur.  <br/>            Lecture/écriture [`ErrorBarValueType`](/slides/python-net/fr/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/has_end_cap/) | Spécifie qu’une extrémité n’est pas dessinée sur les barres d’erreur.<br/>            Lecture/écriture **bool**. |
| [`value`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/value/) | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d’erreur. <br/>            Dans tout autre cas, renverra NaN.<br/>            Lecture/écriture **float**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/format/) | Représente le format des barres d’erreur.<br/>            Lecture/écriture [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/is_visible/) | Obtient ou définit la visibilité des barres d’erreur.<br/>            Lecture/écriture **bool**. |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
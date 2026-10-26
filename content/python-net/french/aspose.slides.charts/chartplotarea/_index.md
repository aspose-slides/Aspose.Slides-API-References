---
title: ChartPlotArea class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea classe

Représente le rectangle où le graphique doit être tracé.

Le type ChartPlotArea expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`format`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/format/) | Renvoie le format d’une zone de tracé.<br/>            Lecture seule [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`x`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/x/) | Renvoie ou définit la coordonnée x du coin supérieur gauche de la boîte englobante de la zone de tracé en tant que fraction de la largeur du graphique (de 0 à 1).<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/y/) | Renvoie ou définit la coordonnée y du coin supérieur gauche de la boîte englobante de la zone de tracé en tant que fraction de la hauteur du graphique (de 0 à 1).<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/width/) | Renvoie ou définit la largeur de la boîte englobante de la zone de tracé en tant que fraction de la largeur du graphique (de 0 à 1).<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/height/) | Renvoie ou définit la hauteur de la boîte englobante de la zone de tracé en tant que fraction de la hauteur du graphique (de 0 à 1).<br/>            Lecture/écriture **float**. |
| [`right`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/right/) | Droite.<br/>            Lecture seule **float**. |
| [`bottom`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/bottom/) | Bas.<br/>            Lecture seule **float**. |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/chart/) | Graphique.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`is_location_autocalculated`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/is_location_autocalculated/) | Définit comment la position doit être calculée : true – calculé automatiquement ; défini par les propriétés X, Y, Width, Height.<br/>            Lecture seule **bool**. |
| [`layout_target_type`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/layout_target_type/) | Si la disposition de la zone de tracé est définie manuellement, cette propriété spécifie si <br/>             la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les étiquettes d'axe) ou par son extérieur<br/>             (en incluant les axes et les étiquettes d'axe).<br/>             Lecture/écriture [`ChartPlotArea.layout_target_type`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/layout_target_type). |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/actual_x/) | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/actual_y/) | Spécifie le haut réel de l'élément du graphique par rapport au coin supérieur gauche du graphique.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/actual_width/) | Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/actual_height/) | Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/chartplotarea/presentation/) |  |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
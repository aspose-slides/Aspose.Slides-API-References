---
title: ChartTitle class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/charttitle/
---
## ChartTitle classe

Represente les propriétés du titre du diagramme.

Le type ChartTitle expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`x`](/slides/python-net/fr/aspose.slides.charts/charttitle/x/) | Renvoie ou définit la coordonnée x d'un titre en tant que fraction de la largeur du diagramme.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides.charts/charttitle/y/) | Renvoie ou définit la coordonnée y d'un titre en tant que fraction de la hauteur du diagramme.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides.charts/charttitle/width/) | Renvoie ou définit la largeur d'un titre en tant que fraction de la largeur du diagramme.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides.charts/charttitle/height/) | Renvoie ou définit la hauteur d'un titre en tant que fraction de la hauteur du diagramme.<br/>            Lecture/écriture **float**. |
| [`right`](/slides/python-net/fr/aspose.slides.charts/charttitle/right/) | Droite.<br/>            Lecture seule **float**. |
| [`bottom`](/slides/python-net/fr/aspose.slides.charts/charttitle/bottom/) | Bas.<br/>            Lecture seule **float**. |
| [`overlay`](/slides/python-net/fr/aspose.slides.charts/charttitle/overlay/) | Détermine si d'autres éléments du diagramme peuvent chevaucher le titre.<br/>            Lecture/écriture **bool**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/charttitle/format/) | Renvoie les styles de remplissage, de ligne et d'effet d'un titre.<br/>            Lecture seule [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/fr/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Peut contenir un texte richement formaté. Si cette propriété n'est pas None alors cette <br/>            valeur de texte formaté remplace le texte généré automatiquement.<br/>            Le texte généré automatiquement est une propriété implicite de l'étiquette de données, de l'étiquette d'unité d'affichage de l'axe des valeurs, du titre de l'axe, du titre du diagramme, de l'étiquette de la droite de tendance.<br/>            Le texte généré automatiquement est formaté avec la propriété IFormattedTextContainer.TextFormat.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/charttitle/text_format/) | Renvoie le format du texte.<br/>            Lecture seule [`IChartTextFormat`](/slides/python-net/fr/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/charttitle/actual_x/) | Spécifie la position x réelle (gauche) de l'élément du diagramme par rapport au coin supérieur gauche du diagramme.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles.<br/>            Lecture **float**. |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/charttitle/actual_y/) | Spécifie le haut réel de l'élément du diagramme par rapport au coin supérieur gauche du diagramme.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles.<br/>            Lecture **float**. |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/charttitle/actual_width/) | Spécifie la largeur réelle de l'élément du diagramme. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles.<br/>            Lecture **float**. |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/charttitle/actual_height/) | Spécifie la hauteur réelle de l'élément du diagramme. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles.<br/>            Lecture **float**. |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/charttitle/chart/) | Renvoie le diagramme parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/charttitle/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fr/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Initialise TextFrameForOverriding avec le texte dans le paramètre "text".<br/>            Si TextFrameForOverriding est déjà initialisé alors il change simplement son texte. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)
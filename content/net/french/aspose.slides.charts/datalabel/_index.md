---
title: DataLabel
second_title: Référence API Aspose.Slides pour .NET
description: Représente des étiquettes de série.
type: docs
weight: 1470
url: /fr/aspose.slides.charts/datalabel/
---

## Classe DataLabel

Représente des étiquettes de série.

```csharp
public class DataLabel : IDataLabel
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Crée une nouvelle instance de la classe DataLabel. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lire Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lire Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lire Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Spécifie le haut réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lire Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Bas. Lecture seule Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Renvoie le graphique parent. Lecture seule [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Renvoie le format de l'étiquette de données. Lecture seule [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Renvoie ou définit la hauteur d'un titre en tant que fraction de la hauteur du graphique. Lecture/écriture Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | Faux signifie que l'étiquette de données n'est pas visible (et donc tous les indicateurs Show*- (ShowValue, ...) sont faux). Lecture seule Boolean. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Droite. Lecture seule Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Renvoie le format du texte. Lecture seule [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Peut contenir un texte au format riche. Si cette propriété n'est pas nulle, alors cette valeur de texte formatée remplace le texte auto-généré de l'étiquette de données. Le texte auto-généré de l'étiquette de données signifie le texte géré par les propriétés ShowSeriesName, ShowValue, ... et est formaté avec la propriété TextFormatManager.TextFormat. Lecture seule [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Obtient ou définit une cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est égale à vrai. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Renvoie ou définit la largeur d'un titre en tant que fraction de la largeur du graphique. Lecture/écriture Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Renvoie ou définit la coordonnée x d'un titre en tant que fraction de la largeur du graphique. Lecture/écriture Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Renvoie ou définit la coordonnée y d'un titre en tant que fraction de la hauteur du graphique. Lecture/écriture Single. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Initialise TextFrameForOverriding avec le texte dans le paramètre "text". Si TextFrameForOverriding est déjà initialisé, il suffit de changer son texte. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Renvoie le texte d'étiquette réel en fonction des paramètres de DataLabelFormat ou de la valeur Text de TextFrameForOverriding. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Rend l'étiquette de données cachée en définissant tous les indicateurs Show*- (ShowValue, ...) sur l'état faux. IsVisible sera faux après cela. |

### Voir aussi

* interface [IDataLabel](../idatalabel)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)
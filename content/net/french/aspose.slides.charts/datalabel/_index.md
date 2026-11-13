---
title: DataLabel
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente les étiquettes d'une série.
type: docs
weight: 1560
url: /fr/aspose.slides.charts/datalabel/
---
## DataLabel classe

Représente les étiquettes d'une série.

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
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Spécifie le haut réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Bas. Lecture seule Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Retourne le graphique parent. Lecture seule [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Retourne le format d'étiquette de données. Lecture seule [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Retourne ou définit la hauteur d'un titre comme une fraction de la hauteur du graphique. Lecture/écriture Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | False signifie que l'étiquette de données n'est pas visible (et donc tous les indicateurs Show*-flags (ShowValue, ...) sont false). Lecture seule Boolean. |
| [LabelShapeType](../../aspose.slides.charts/datalabel/labelshapetype) { get; set; } | Obtient ou définit le type de forme de l'étiquette de données. Retourne NotDefined si aucune forme n'est définie. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Droite. Lecture seule Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Retourne le format de texte. Lecture seule [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Peut contenir un texte riche formaté. Si cette propriété n'est pas null, alors cette valeur de texte formaté remplace le texte auto-généré de l'étiquette de données. Le texte auto-généré de l'étiquette de données désigne le texte géré par les propriétés ShowSeriesName, ShowValue, ... et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est true. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Retourne ou définit la largeur d'un titre comme une fraction de la largeur du graphique. Lecture/écriture Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Retourne ou définit la coordonnée x d'un titre comme une fraction de la largeur du graphique. Lecture/écriture Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Retourne ou définit la coordonnée y d'un titre comme une fraction de la hauteur du graphique. Lecture/écriture Single. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Initialise TextFrameForOverriding avec le texte du paramètre "text". Si TextFrameForOverriding est déjà initialisé, alors modifie simplement son texte. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Retourne le texte réel de l'étiquette basé sur les paramètres DataLabelFormat ou la valeur TextFrameForOverriding.Text. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Rend l'étiquette de données invisible en définissant tous les indicateurs Show*-flags (ShowValue, ...) à l'état false. IsVisible sera false après cela. |

### Voir aussi

* interface [IDataLabel](../idatalabel)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
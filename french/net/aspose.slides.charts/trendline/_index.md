---
title: Trendline
second_title: Référence de l'API Aspose.Slides pour .NET
description: La classe représente la ligne de tendance de la série de graphiques
type: docs
weight: 2350
url: /fr/net/aspose.slides.charts/trendline/
---
## Trendline class

La classe représente la ligne de tendance de la série de graphiques

```csharp
public class Trendline : DomObject<TrendlineCollection>, ITrendline
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Backward](../../aspose.slides.charts/trendline/backward) { get; set; } | Spécifie le nombre de catégories (ou d'unités sur un graphique en nuage de points) que la ligne de tendance étend avant les données de la série en cours de tendance. Sur les graphiques en nuage de points et non en nuage de points, la valeur doit être toute valeur non négative . Lecture/écritureDouble . |
| [Chart](../../aspose.slides.charts/trendline/chart) { get; } | Renvoie le graphique parent. Lecture seule[`IChart`](../ichart) . |
| [DisplayEquation](../../aspose.slides.charts/trendline/displayequation) { get; set; } | Spécifie que l'équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). Lecture/écritureBoolean . |
| [DisplayRSquaredValue](../../aspose.slides.charts/trendline/displayrsquaredvalue) { get; set; } | Spécifie que la valeur R au carré de la courbe de tendance est affichée sur le graphique (dans la même étiquette que l'équation). Lecture/écritureBoolean . |
| [Format](../../aspose.slides.charts/trendline/format) { get; set; } | Représente le format de la ligne de tendance. Lecture/écriture[`IFormat`](../iformat) . |
| [Forward](../../aspose.slides.charts/trendline/forward) { get; set; } | Spécifie le nombre de catégories (ou d'unités sur un graphique en nuage de points) que la ligne de tendance s'étend après les données pour la série qui fait l'objet d'une tendance. Sur les graphiques en nuage de points et non en nuage de points, la valeur doit être toute valeur non négative . Lecture/écritureDouble . |
| [Intercept](../../aspose.slides.charts/trendline/intercept) { get; set; } | Spécifie la valeur où la ligne de tendance doit croiser l'axe y. Cette propriété doit être prise en charge uniquement lorsque le type de courbe de tendance est exp, linéaire ou poly. Lecture/écritureDouble . |
| [Order](../../aspose.slides.charts/trendline/order) { get; set; } | Spécifie l'ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de courbes de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écritureByte . |
| [Period](../../aspose.slides.charts/trendline/period) { get; set; } | Spécifie la période de la ligne de tendance pour une ligne de tendance moyenne mobile. Il est ignoré pour les autres variantes de ligne trend . La valeur doit être comprise entre 2 et 255. Lecture/écritureByte . |
| [RelatedLegendEntry](../../aspose.slides.charts/trendline/relatedlegendentry) { get; } | Représente l'entrée de légende liée à cette ligne de tendance Lecture seule[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [TextFormat](../../aspose.slides.charts/trendline/textformat) { get; } | Renvoie le format texte. Lecture seule[`IChartTextFormat`](../icharttextformat) . |
| [TextFrameForOverriding](../../aspose.slides.charts/trendline/textframeforoverriding) { get; } | Peut contenir un texte formaté enrichi. Si cette propriété n'est pas nulle, cette valeur de texte au format remplace le texte généré automatiquement de l'étiquette de données. Le texte généré automatiquement de l'étiquette de données signifie un texte géré par les propriétés ShowSeriesName, ShowValue, ... et mis en forme avec le TextFormatManager Propriété .TextFormat. Lecture seule[`ITextFrame`](../../aspose.slides/itextframe) . |
| [TrendlineName](../../aspose.slides.charts/trendline/trendlinename) { get; set; } | Obtient ou définit le nom de la courbe de tendance. Lecture/écritureString . |
| [TrendlineType](../../aspose.slides.charts/trendline/trendlinetype) { get; set; } | Obtient ou définit le type de ligne de tendance. Lecture/écriture[`TrendlineType`](../trendlinetype) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/trendline/addtextframeforoverriding)(string) | Initialiser TextFrameForOverriding avec le texte dans le paramètre "text". Si TextFrameForOverriding est déjà initialisé alors change simplement son texte. |

### Voir également

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [TrendlineCollection](../trendlinecollection)
* interface [ITrendline](../itrendline)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
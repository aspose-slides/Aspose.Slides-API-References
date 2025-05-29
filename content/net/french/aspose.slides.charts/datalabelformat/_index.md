---
title: DataLabelFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les options de formatage pour DataLabel.
type: docs
weight: 1490
url: /fr/aspose.slides.charts/datalabelformat/
---

## Classe DataLabelFormat

Représente les options de formatage pour DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Renvoie le graphique. Lecture seule [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Représente le format de l'étiquette de données. Lecture seule [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean en lecture/écriture. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Représente la position de l'étiquette de données. Lecture/écriture [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Représente le comportement d'affichage de la valeur de taille de bulle de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur de la taille de bulle. Faux pour cacher. Lecture/écriture Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. Vrai pour afficher le nom de la catégorie pour les étiquettes de données sur un graphique. Faux pour cacher. Lecture/écriture Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Détermine si l'étiquette de données du graphique spécifié sera affichée comme un appel de données ou comme une étiquette de données.  Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données dans la collection DataLabelCollection (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" provoque que toutes DataLabels[i].ShowLabelAsDataCallout soient égales à val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Représente le comportement d'affichage de la valeur de cellule de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur de la cellule. Faux pour cacher. Lecture/écriture Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Représente le comportement d'affichage des lignes directrices de l'étiquette de données d'un graphique spécifié. Vrai affiche les lignes directrices. Faux pour cacher. Lecture/écriture Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. Vrai si la clé de légende de l'étiquette de données est visible. Lecture/écriture Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur de pourcentage. Faux pour cacher. Lecture/écriture Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Renvoie ou définit un Boolean pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. Vrai pour afficher le nom de la série. Faux pour cacher. Lecture/écriture Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur de pourcentage. Faux pour cacher. Lecture/écriture Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Renvoie le format de texte du graphique. Lecture seule [`IChartTextFormat`](../icharttextformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir aussi

* classe [PVIObject](../../aspose.slides/pviobject)
* interface [IDataLabelFormat](../idatalabelformat)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
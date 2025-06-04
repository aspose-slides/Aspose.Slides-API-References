---
title: DataLabelFormat
second_title: Aspose.Slides pour .NET API Référence
description: Représente les options de formatage pour DataLabel.
type: docs
weight: 1490
url: /fr/aspose.slides.charts/datalabelformat/
---

## DataLabelFormat class

Représente les options de formatage pour DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. En lecture seule [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Renvoie le graphique. En lecture seule [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Représente le format de l'étiquette de données. En lecture seule [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Booléen en lecture/écriture. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Représente la chaîne de format pour l'objet DataLabels. Chaîne en lecture/écriture. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Représente la position de l'étiquette de données. En lecture/écriture [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Chaîne en lecture/écriture. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Représente le comportement d'affichage de la valeur de taille de bulle de l'étiquette de données d'un graphique spécifié. True affiche la valeur de taille de bulle. False pour masquer. Booléen en lecture/écriture. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Booléen en lecture/écriture. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Détermine si l'étiquette de données du graphique spécifié sera affichée comme un appel de données ou comme une étiquette de données. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données dans la collection DataLabelCollection (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" cause à ce que tous DataLabels[i].ShowLabelAsDataCallout soit égal à val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Représente le comportement d'affichage de la valeur de cellule de l'étiquette de données d'un graphique spécifié. True affiche la valeur de cellule. False pour masquer. Booléen en lecture/écriture. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Représente le comportement d'affichage de lignes de leader pour l'étiquette de données d'un graphique spécifié. True affiche les lignes de leader. False pour masquer. Booléen en lecture/écriture. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Booléen en lecture/écriture. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Booléen en lecture/écriture. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Renvoie ou définit un booléen pour indiquer le comportement d'affichage du nom de série pour les étiquettes de données sur un graphique. True pour montrer le nom de série. False pour masquer. Booléen en lecture/écriture. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Représente le comportement d'affichage de la valeur de l'étiquette de données d'un graphique spécifié. True affiche la valeur. False pour masquer. Booléen en lecture/écriture. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Renvoie le format de texte du graphique. En lecture seule [`IChartTextFormat`](../icharttextformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir Aussi

* class [PVIObject](../../aspose.slides/pviobject)
* interface [IDataLabelFormat](../idatalabelformat)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
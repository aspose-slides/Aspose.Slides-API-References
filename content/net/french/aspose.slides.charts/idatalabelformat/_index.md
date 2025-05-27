---
title: IDataLabelFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les options de formatage pour DataLabel.
type: docs
weight: 1960
url: /fr/aspose.slides.charts/idatalabelformat/
---

## Interface IDataLabelFormat

Représente les options de formatage pour DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. En lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Représente le format de l'étiquette de données. En lecture seule [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Booléen en lecture/écriture. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Représente la chaîne de format pour l'objet DataLabels. Chaîne en lecture/écriture. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Représente la position de l'étiquette de données. En lecture/écriture [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Définit ou retourne une variante représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Chaîne en lecture/écriture. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Représente le comportement d'affichage de la valeur de taille de bulle de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur de taille de bulle. Faux pour cacher. Booléen en lecture/écriture. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. Vrai pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. Faux pour cacher. Booléen en lecture/écriture. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Détermine si l'étiquette de données du graphique spécifié sera affichée comme un appel de données ou comme une étiquette de données. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données dans la collection DataLabelCollection (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" cause à toutes DataLabels[i].ShowLabelAsDataCallout soit égal à val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Représente le comportement d'affichage de la valeur de cellule de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur de la cellule. Faux pour cacher. Booléen en lecture/écriture. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Représente le comportement d'affichage des lignes de leader de l'étiquette de données d'un graphique spécifié. Vrai affiche les lignes de leader. Faux pour cacher. Booléen en lecture/écriture. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. Vrai si la clé de légende de l'étiquette de données est visible. Booléen en lecture/écriture. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur en pourcentage. Faux pour cacher. Booléen en lecture/écriture. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Retourne ou définit un booléen pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. Vrai pour montrer le nom de la série. Faux pour cacher. Booléen en lecture/écriture. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Représente le comportement d'affichage de la valeur de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur. Faux pour cacher. Booléen en lecture/écriture. |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
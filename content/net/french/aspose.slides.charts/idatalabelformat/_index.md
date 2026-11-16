---
title: IDataLabelFormat
second_title: Aspose.Sildes pour la référence API .NET
description: Représente les options de mise en forme pour DataLabel.
type: docs
weight: 2060
url: /fr/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interface

Représente les options de mise en forme pour DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Permet d’obtenir l’interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Représente le format de l’étiquette de données. Lecture seule [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lecture/écriture Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Représente la chaîne de format pour l’objet DataLabels. Lecture/écriture String. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Représente la position de l’étiquette de données. Lecture/écriture [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Représente le comportement d’affichage de la valeur de la taille de la bulle d’étiquette de données d’un graphique spécifié. True affiche la valeur de la taille de la bulle. False masque. Lecture/écriture Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Représente le comportement d’affichage du nom de catégorie d’étiquette de données d’un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Lecture/écriture Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Détermine si l’étiquette de données du graphique spécifié sera affichée comme une annotation de données ou comme une étiquette de données. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" entraîne que tous les DataLabels[i].ShowLabelAsDataCallout sont égaux à val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Représente le comportement d’affichage de la valeur de cellule d’une étiquette de données d’un graphique spécifié. True affiche la valeur de la cellule. False masque. Lecture/écriture Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Représente le comportement d’affichage des lignes de repère d’une étiquette de données d’un graphique spécifié. True affiche les lignes de repère. False masque. Lecture/écriture Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Représente le comportement d’affichage de la clé de légende d’une étiquette de données d’un graphique spécifié. True si la clé de légende de l’étiquette de données est visible. Lecture/écriture Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Représente le comportement d’affichage de la valeur de pourcentage d’une étiquette de données d’un graphique spécifié. True affiche la valeur en pourcentage. False masque. Lecture/écriture Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Renvoie ou définit un Boolean indiquant le comportement d’affichage du nom de série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour masquer. Lecture/écriture Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Représente le comportement d’affichage de la valeur de pourcentage d’une étiquette de données d’un graphique spécifié. True affiche la valeur en pourcentage. False masque. Lecture/écriture Boolean. |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
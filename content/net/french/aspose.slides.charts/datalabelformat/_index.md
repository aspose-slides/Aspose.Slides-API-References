---
title: DataLabelFormat
second_title: Référence API Aspose.Sildes pour .NET
description: Représente les options de formatage pour DataLabel.
type: docs
weight: 1570
url: /fr/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat classe

Représente les options de formatage pour DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface de base IPresentationComponent. Lecture seule [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Renvoie le graphique. Lecture seule [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Représente le format de l'étiquette de données. Lecture seule [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Lecture/écriture Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Représente la position de l'étiquette de données. Lecture/écriture [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Représente le comportement d'affichage de la valeur de taille de bulle de l'étiquette de données d'un graphique spécifié. True affiche la valeur de taille de bulle. False pour masquer. Lecture/écriture Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie. False pour masquer. Lecture/écriture Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Détermine si l'étiquette de données d'un graphique spécifié sera affichée comme appel de données ou comme étiquette de données. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. La définir avec une valeur met également à jour la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire « DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val » entraîne que tous les DataLabels[i].ShowLabelAsDataCallout sont égaux à val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Représente le comportement d'affichage de la valeur de cellule de l'étiquette de données d'un graphique spécifié. True affiche la valeur de cellule. False pour masquer. Lecture/écriture Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Représente le comportement d'affichage des lignes directrices de l'étiquette de données d'un graphique spécifié. True affiche les lignes directrices. False pour masquer. Lecture/écriture Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. True si la clé de légende est visible. Lecture/écriture Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Renvoie ou définit un Boolean indiquant le comportement d'affichage du nom de série pour les étiquettes de données sur un graphique. True pour afficher le nom de série. False pour masquer. Lecture/écriture Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Renvoie le format de texte du graphique. Lecture seule [`IChartTextFormat`](../icharttextformat). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir aussi

* classe [PVIObject](../../aspose.slides/pviobject)
* interface [IDataLabelFormat](../idatalabelformat)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
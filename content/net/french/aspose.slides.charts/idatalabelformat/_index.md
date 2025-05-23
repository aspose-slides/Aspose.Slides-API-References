---
title: IDataLabelFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les options de formatage pour DataLabel.
type: docs
weight: 1920
url: /fr/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interface

Représente les options de formatage pour DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface IFormattedTextContainer de base. Lecture seule[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Représente le format de l'étiquette de données. Lecture seule[`IFormat`](../iformat) . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lecture/écritureBoolean . |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Représente la chaîne de format de l'objet DataLabels. Lecture/écritureString . |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Représente la position de l'étiquette de données. Lecture/écriture[`LegendDataLabelPosition`](../legenddatalabelposition) . |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écritureString . |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Représente le comportement d'affichage de la valeur de taille de bulle de l'étiquette de données d'un graphique spécifié. True affiche la valeur de taille de bulle. Faux pour masquer. Lecture/écritureBoolean . |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie des étiquettes de données d'un graphique. Faux pour masquer. Lecture/écritureBoolean . |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Détermine que l'étiquette de données du graphique spécifié sera affichée en tant que légende de données ou en tant qu'étiquette de données.  Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définissez cette propriété avec la valeur définit également cette valeur sur Propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val ;" provoque tous les DataLabels[i].ShowLabelAsDataCallout est égal à val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un graphique spécifié. True affiche la valeur de la cellule. Faux pour masquer. Lecture/écritureBoolean . |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Représente le comportement d'affichage des lignes de repère des étiquettes de données d'un graphique spécifié. True affiche les lignes de repère. Faux pour masquer. Lecture/écritureBoolean . |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. Vrai si la clé de légende de l'étiquette de données est visible. Lecture/écritureBoolean . |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur en pourcentage. Faux pour masquer. Lecture/écritureBoolean . |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Renvoie ou définit un booléen pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. Faux pour masquer. Lecture/écritureBoolean . |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur en pourcentage. Faux pour masquer. Lecture/écritureBoolean . |

### Voir également

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

---
title: LoadOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement dune présentation.
type: docs
weight: 7170
url: /fr/net/aspose.slides/loadoptions/
---
## LoadOptions class

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d'une présentation.

```csharp
public class LoadOptions : ILoadOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Crée de nouvelles options de chargement par défaut. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Crée de nouvelles options de chargement. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Représente les options qui peuvent être utilisées pour gérer le comportement de gestion des objets binaires volumineux (BLOB), comme l'utilisation de fichiers temporaires ou le nombre maximal d'octets BLOB en mémoire. Ces options visaient à configurer le meilleur rapport performances/consommation de mémoire pour un environnement ou des exigences spécifiques. Un grand objet binaire (BLOB) est une donnée binaire stockée en tant qu'entité unique - c'est-à-dire que BLOB peut être un audio, une vidéo ou une présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée dans le cas où la police source est introuvable. Lecture/écritureString . |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police normale utilisée dans le cas où la police source est introuvable. Lecture/écritureString . |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police de symbole utilisée dans le cas où la police source est introuvable. Lecture/écritureString . |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation tout au long de sa durée de vie et ne sont pas partagées avec d'autres présentations |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Le jeton à surveiller pour les demandes d'interruption.  Ce jeton gère l'ensemble[`IPresentation`](../ipresentation)durée de vie des instances. Toute opération de longue durée, comme le chargement de ou l'enregistrement d'une présentation, sera interrompue par l'appel du[`Interrupt`](../interruptiontokensource/interrupt) méthode de le[`InterruptionTokenSource`](../interruptiontokensource) . |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Renvoie ou définit le format d'une présentation à charger. Lecture/écriture[`LoadFormat`](../loadformat) . |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et le mot de passe doit être ignoré. La valeur false signifie que toute la présentation chiffrée doit être chargée avec utilisation du droit mot de passe. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est vraie, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lire écrireBoolean . |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtient ou définit le mot de passe. Lecture/écritureString . |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Renvoie ou définit l'interface de rappel qui gère le chargement des ressources externes. Lecture/écriture[`IResourceLoadingCallback`](../iresourceloadingcallback) . |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Récupère les options pour les feuilles de calcul. Par exemple, ces options affectent les formules de calcul des graphiques. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide si le chargement du processus se poursuivra ou sera abandonné. Lecture/écriture[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Voir également

* interface [ILoadOptions](../iloadoptions)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
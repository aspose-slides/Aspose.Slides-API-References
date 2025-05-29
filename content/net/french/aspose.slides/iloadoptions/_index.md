---
title: ILoadOptions
second_title: Référence API Aspose.Slides pour .NET
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
weight: 6140
url: /fr/aspose.slides/iloadoptions/
---

## Interface ILoadOptions

Permet de spécifier des options supplémentaires (comme le format ou la police par défaut) lors du chargement d'une présentation.

```csharp
public interface ILoadOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Représente les options pouvant être utilisées pour gérer le comportement de traitement des objets binaires volumineux (BLOB), telles que l'utilisation de fichiers temporaires ou le nombre maximal de bytes BLOB en mémoire. Ces options visent à configurer le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particuliers. Un objet binaire volumineux (BLOB) est une donnée binaire stockée en tant qu'entité unique - c'est-à-dire qu'un BLOB peut être un fichier audio, vidéo ou la présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée en cas d'absence de la police source. Chaîne en lecture-écriture. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police régulière utilisée en cas d'absence de la police source. Chaîne en lecture-écriture. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police de symbole utilisée en cas d'absence de la police source. Chaîne en lecture-écriture. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Renvoie ou définit la langue par défaut pour le texte de la présentation. Chaîne en lecture/écriture. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Détermine si Aspose.Slides doit supprimer tous les objets binaires intégrés lors du chargement de la présentation. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources de polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation tout au long de sa durée de vie et ne sont pas partagées avec d'autres présentations. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Le jeton à surveiller pour les requêtes d'interruption. Ce jeton gère l'ensemble de la durée de vie de l'instance [`IPresentation`](../ipresentation). Toute opération de longue durée, telle que le chargement ou la sauvegarde de la présentation, sera interrompue par l'appel de la méthode [`Interrupt`](../iinterruptiontokensource/interrupt) de l'[`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Renvoie ou définit le format d'une présentation à charger. Lecture/écriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. Une valeur de vrai signifie que seules les propriétés du document doivent être chargées depuis un fichier de présentation chiffré et que le mot de passe doit être ignoré. Une valeur de faux signifie que l'ensemble de la présentation chiffrée doit être chargée avec le bon mot de passe. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est vraie, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Boolean en lecture-écriture. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Obtient ou définit le mot de passe. Chaîne en lecture-écriture. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Renvoie ou définit l'interface callback qui gère le chargement des ressources externes. Lecture/écriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Représente les options pouvant être utilisées pour spécifier le comportement supplémentaire des feuilles de calcul. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide si le processus de chargement se poursuivra ou sera interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
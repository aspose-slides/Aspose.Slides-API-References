---
title: ILoadOptions
second_title: Aspose.Sildes pour .NET API Référence
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
weight: 6140
url: /fr/aspose.slides/iloadoptions/
---

## Interface ILoadOptions

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d'une présentation.

```csharp
public interface ILoadOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Représente les options qui peuvent être utilisées pour gérer le comportement de gestion des objets binaires volumineux (BLOBs), tels que l'utilisation de fichiers temporaires ou le maximum d'octets de BLOBs en mémoire. Ces options sont destinées à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particuliers. Un objet binaire volumineux (BLOB) est une donnée binaire stockée comme une entité unique - c'est-à-dire qu'un BLOB peut être un audio, une vidéo ou la présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Récupère ou définit la police asiatique utilisée en cas de non-trouvabilité de la police source. Chaîne en lecture-écriture. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Récupère ou définit la police régulière utilisée en cas de non-trouvabilité de la police source. Chaîne en lecture-écriture. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Récupère ou définit la police symbole utilisée en cas de non-trouvabilité de la police source. Chaîne en lecture-écriture. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Récupère ou définit la langue par défaut pour le texte de la présentation. Chaîne en lecture-écriture. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources pour les polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation tout au long de sa durée de vie et ne sont pas partagées avec d'autres présentations. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Le jeton à surveiller pour les demandes d'interruption. Ce jeton gère l'ensemble du cycle de vie de l'instance [`IPresentation`](../ipresentation). Toute opération de longue durée, telle que le chargement ou l'enregistrement d'une présentation, sera interrompue par l'appel de la méthode [`Interrupt`](../iinterruptiontokensource/interrupt) de [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Récupère ou définit le format d'une présentation à charger. Lecture/écriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe. Une valeur de true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré. Une valeur de false signifie que l'ensemble de la présentation chiffrée doit être chargé avec l'utilisation du bon mot de passe. Si la présentation n'est pas chiffrée, alors la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Booléen en lecture-écriture. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Récupère ou définit le mot de passe. Chaîne en lecture-écriture. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Récupère ou définit l'interface de rappel qui gère le chargement de ressources externes. Lecture/écriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Représente les options qui peuvent être utilisées pour spécifier un comportement supplémentaire pour les feuilles de calcul. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Récupère ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
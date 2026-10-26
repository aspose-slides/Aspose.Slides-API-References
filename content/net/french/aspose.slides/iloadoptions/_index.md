---
title: ILoadOptions
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d’une présentation.
type: docs
weight: 6340
url: /fr/aspose.slides/iloadoptions/
---
## ILoadOptions interface

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d’une présentation.

```csharp
public interface ILoadOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Représente les options qui peuvent être utilisées pour gérer le comportement de manipulation des Binary Large Objects (BLOB), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. Ces options visent à définir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières. Un Binary Large Object (BLOB) est une donnée binaire stockée en tant qu’entité unique – c.-à-d. un BLOB peut être un audio, une vidéo ou la présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée si la police source n’est pas trouvée. Chaîne en lecture-écriture. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police régulière utilisée si la police source n’est pas trouvée. Chaîne en lecture-écriture. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police de symbole utilisée si la police source n’est pas trouvée. Chaîne en lecture-écriture. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Renvoie ou définit la langue par défaut du texte de la présentation. Chaîne en lecture/écriture. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d’autres présentations. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Le jeton à surveiller pour les demandes d’interruption. Ce jeton gère la durée de vie de toute instance [`IPresentation`](../ipresentation). Toute opération de longue durée, telle que le chargement ou l’enregistrement d’une présentation, sera interrompue en appelant la méthode [`Interrupt`](../iinterruptiontokensource/interrupt) du [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Renvoie ou définit le format d’une présentation à charger. Lecture/écriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d’un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que toute la présentation chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d’un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, les propriétés du document ne peuvent pas être chargées et une exception sera levée. Booléen en lecture-écriture. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Renvoie ou définit le mot de passe. Chaîne en lecture-écriture. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Représente les options qui peuvent être utilisées pour spécifier le comportement supplémentaire des feuilles de calcul. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être abandonné. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
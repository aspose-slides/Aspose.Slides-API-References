---
title: LoadOptions
second_title: Aspose.Sildes pour .NET Référence API
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
weight: 7860
url: /fr/aspose.slides/loadoptions/
---
## classe LoadOptions

Permet de spécifier des options supplémentaires (comme le format ou la police par défaut) lors du chargement d'une présentation.

```csharp
public class LoadOptions : ILoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Crée de nouvelles options de chargement par défaut. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Crée de nouvelles options de chargement. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Représente les options qui peuvent être utilisées pour gérer le comportement de traitement des Binary Large Objects (BLOBs), comme l'utilisation de fichiers temporaires ou le nombre maximal d'octets BLOB en mémoire. Ces options sont destinées à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières. Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique - c’est-à-dire qu’un BLOB peut être un audio, une vidéo ou la présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée si la police source n'est pas trouvée. Lecture/écriture String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police standard utilisée si la police source n'est pas trouvée. Lecture/écriture String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police Symbol utilisée si la police source n'est pas trouvée. Lecture/écriture String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Renvoie ou définit la langue par défaut du texte de la présentation. Lecture/écriture String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d'autres présentations. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Le jeton permettant de surveiller les demandes d'interruption. Ce jeton gère toute la durée de vie de l'instance [`IPresentation`](../ipresentation). Toute opération de longue durée, comme le chargement ou l'enregistrement d'une présentation, sera interrompue en appelant la méthode [`Interrupt`](../interruptiontokensource/interrupt) de [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Renvoie ou définit le format d'une présentation à charger. Lecture/écriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation crypté et que le mot de passe doit être ignoré. La valeur false signifie que l'ensemble de la présentation cryptée doit être chargé en utilisant le bon mot de passe. Si la présentation n'est pas cryptée, alors la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier crypté ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtient ou définit le mot de passe. Lecture/écriture String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Renvoie ou définit l'interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtient les options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* interface [ILoadOptions](../iloadoptions)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
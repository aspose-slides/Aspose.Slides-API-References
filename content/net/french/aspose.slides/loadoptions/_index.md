---
title: LoadOptions
second_title: Aspose.Sildes pour .NET Référence API
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
weight: 7600
url: /fr/aspose.slides/loadoptions/
---

## LoadOptions class

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d'une présentation.

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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Représente les options qui peuvent être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOBs), comme l'utilisation de fichiers temporaires ou le nombre maximum d'octets de BLOB en mémoire. Ces options visent à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières. Un objet binaire volumineux (BLOB) est des données binaires stockées en tant qu'entité unique - c'est-à-dire qu'un BLOB peut être un audio, une vidéo ou une présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée en cas d'absence de la police source. Lecture/écriture String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police régulière utilisée en cas d'absence de la police source. Lecture/écriture String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police de symbole utilisée en cas d'absence de la police source. Lecture/écriture String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Renvoie ou définit la langue par défaut pour le texte de la présentation. Lecture/écriture String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources pour les polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation tout au long de sa durée de vie et ne sont pas partagées avec d'autres présentations |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Le jeton pour surveiller les demandes d'interruption.  Ce jeton gère l'ensemble de la durée de vie de l'instance [`IPresentation`](../ipresentation). Toute opération longue, telle que le chargement ou l'enregistrement de la présentation, sera interrompue par l'appel de la méthode [`Interrupt`](../interruptiontokensource/interrupt) de [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Renvoie ou définit le format d'une présentation à charger. Lecture/écriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété a un sens si le fichier de présentation est protégé par un mot de passe. Une valeur vraie signifie que seules les propriétés du document doivent être chargées depuis un fichier de présentation crypté et que le mot de passe doit être ignoré. Une valeur fausse signifie que l'ensemble de la présentation cryptée doit être chargée en utilisant le bon mot de passe. Si la présentation n'est pas cryptée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier crypté ne sont pas publiques et que la valeur de la propriété est vraie, les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtient ou définit le mot de passe. Lecture/écriture String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Renvoie ou définit l'interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtient les options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide de la poursuite ou de l'abandon du processus de chargement. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* interface [ILoadOptions](../iloadoptions)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
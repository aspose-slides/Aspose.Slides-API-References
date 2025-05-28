---
title: LoadOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
weight: 7600
url: /fr/aspose.slides/loadoptions/
---

## Classe LoadOptions

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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Représente les options qui peuvent être utilisées pour gérer le comportement de gestion des objets binaires volumineux (BLOBs), comme l'utilisation de fichiers temporaires ou le nombre maximal d'octets de BLOBs en mémoire. Ces options visent à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières. Un objet binaire volumineux (BLOB) est une donnée binaire stockée comme une seule entité - c'est-à-dire qu'un BLOB peut être un audio, une vidéo ou la présentation elle-même. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée en cas de non disponibilité de la police source. Lecture/écriture String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police régulière utilisée en cas de non disponibilité de la police source. Lecture/écriture String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police symbolique utilisée en cas de non disponibilité de la police source. Lecture/écriture String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Renvoie ou définit la langue par défaut pour le texte de la présentation. Lecture/écriture String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Spécifie les sources pour les polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d'autres présentations. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Le jeton pour surveiller les demandes d'interruption. Ce jeton gère l'ensemble de la durée de vie de l'instance [`IPresentation`](../ipresentation). Toute opération longue, telle que le chargement ou l'enregistrement d'une présentation, sera interrompue en appelant la méthode [`Interrupt`](../interruptiontokensource/interrupt) de [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Renvoie ou définit le format d'une présentation à charger. Lecture/écriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriété est pertinente si le fichier de présentation est protégé par mot de passe. Une valeur vraie signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré. Une valeur fausse signifie que l'ensemble de la présentation chiffrée doit être chargée avec le mot de passe correct. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est vraie, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtenez ou définissez le mot de passe. Lecture/écriture String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Renvoie ou définit l'interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtenez des options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide si le processus de chargement continuera ou sera interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* interface [ILoadOptions](../iloadoptions)
* espace de noms [Aspose.Slides](../../aspose.slides)
* ensemble [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
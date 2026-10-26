---
title: LoadOptions
second_title: Référence API Aspose.Sildes pour .NET
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
weight: 7840
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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Représente les options pouvant être utilisées pour gérer le comportement de manipulation des Binary Large Objects (BLOBs), comme l'utilisation de fichiers temporaires ou le nombre maximal d'octets BLOB en mémoire. Ces options visent à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières. Un Binary Large Object (BLOB) est une donnée binaire stockée en tant qu'entité unique - c'est a dire qu'un BLOB peut être un audio, une video ou la présentation elle-meme. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Renvoie ou définit la police asiatique utilisée si la police source n'est pas trouvee. Lecture/ecriture String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police standard utilisée si la police source n'est pas trouvee. Lecture/ecriture String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Renvoie ou définit la police symbole utilisée si la police source n'est pas trouvee. Lecture/ecriture String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Renvoie ou définit la langue par defaut pour le texte de la presentation. Lecture/ecriture String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determine si Aspose.Slides supprimera tous les objets binaires integrates lors du chargement de la presentation. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Specifie les sources des polices externes a utiliser par la presentation. Ces polices sont disponibles pour la presentation pendant toute sa duree de vie et ne sont pas partagees avec d'autres presentations. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Le jeton permettant de surveiller les demandes d'interruption. Ce jeton gere la duree de vie entiere de l'instance [`IPresentation`](../ipresentation). Toute operation de longue duree, telle que le chargement ou l'enregistrement de la presentation, sera interrompue en appelant la methode [`Interrupt`](../interruptiontokensource/interrupt) du [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Renvoie ou definit le format d'une presentation a charger. Lecture/ecriture [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Cette propriete a du sens si le fichier de presentation est protege par un mot de passe. La valeur true signifie que seules les proprietes du document doivent etre chargees a partir d'un fichier de presentation chiffre et que le mot de passe doit etre ignore. La valeur false signifie que toute la presentation chiffre doit etre chargee en utilisant le mot de passe correct. Si la presentation n'est pas chiffre, la valeur de la propriete est toujours ignoree. Si les proprietes du document d'un fichier chiffre ne sont pas publiques et que la valeur de la propriete est true, les proprietes du document ne peuvent pas etre chargees et une exception sera levee. Lecture/ecriture Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Renvoie ou definit le mot de passe. Lecture/ecriture String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Renvoie ou definit l'interface de rappel qui gere le chargement des ressources externes. Lecture/ecriture [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtient les options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Renvoie ou definit un objet qui reçoit les avertissements et decide si le processus de chargement doit se poursuivre ou être abandonne. Lecture/ecriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* interface [ILoadOptions](../iloadoptions)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: PptOptions
second_title: Aspose.Slides pour .NET Référence API
description: Fournit des options qui contrôlent comment une présentation est enregistrée au format PPT.
type: docs
weight: 4170
url: /fr/aspose.slides.export/pptoptions/
---

## Classe PptOptions

Fournit des options qui contrôlent comment une présentation est enregistrée au format PPT.

```csharp
public class PptOptions : SaveOptions, IPptOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PptOptions](pptoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée si la police source est introuvable. Chaîne lisible et écrite. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression d'enregistrement en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RootDirectoryClsid](../../aspose.slides.export/pptoptions/rootdirectoryclsid) { get; set; } | Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les liens hypertexte avec des appels JavaScript lors de l'enregistrement de la présentation. Booléen lisible et écrite. La valeur par défaut est **false**. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* classe [SaveOptions](../saveoptions)
* interface [IPptOptions](../ipptoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
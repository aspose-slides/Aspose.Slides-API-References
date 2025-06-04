---
title: MarkdownSaveOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les options qui contrôlent la façon dont la présentation doit être enregistrée en markdown.
type: docs
weight: 4080
url: /fr/aspose.slides.export/markdownsaveoptions/
---

## Classe MarkdownSaveOptions

Représente les options qui contrôlent la façon dont la présentation doit être enregistrée en markdown.

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Ctor. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasePath](../../aspose.slides.export/markdownsaveoptions/basepath) { get; set; } | Spécifie le chemin de base où le document avec les ressources sera enregistré. La valeur par défaut est le répertoire actuel de l'application. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée si la police source n'est pas trouvée. Chaîne en lecture/écriture. |
| [ExportType](../../aspose.slides.export/markdownsaveoptions/exporttype) { get; set; } | Spécifie la spécification markdown pour convertir la présentation. La valeur par défaut est `TextOnly`. |
| [Flavor](../../aspose.slides.export/markdownsaveoptions/flavor) { get; set; } | Spécifie la spécification markdown pour convertir la présentation. La valeur par défaut est `Multi-markdown`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du gradient. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [HandleRepeatedSpaces](../../aspose.slides.export/markdownsaveoptions/handlerepeatedspaces) { get; set; } |  |
| [ImagesSaveFolderName](../../aspose.slides.export/markdownsaveoptions/imagessavefoldername) { get; set; } | Spécifie le nom du dossier pour enregistrer les images. La valeur par défaut est `Images`. |
| [NewLineType](../../aspose.slides.export/markdownsaveoptions/newlinetype) { get; set; } | Spécifie si le document généré doit avoir des nouvelles lignes \\r(Macintosh) ou \\n(Unix) ou \\r\\n(Windows). La valeur par défaut est `Unix`. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression d'enregistrement en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RemoveEmptyLines](../../aspose.slides.export/markdownsaveoptions/removeemptylines) { get; set; } | Si défini sur `true`, supprime les lignes vides ou contenant uniquement des espaces du Markdown final. La valeur par défaut est `false`. |
| [ShowComments](../../aspose.slides.export/markdownsaveoptions/showcomments) { get; set; } | Spécifie si le document généré doit afficher des commentaires ou non. La valeur par défaut est `false`. |
| [ShowHiddenSlides](../../aspose.slides.export/markdownsaveoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure des diapositives cachées ou non. La valeur par défaut est `false`. |
| [ShowSlideNumber](../../aspose.slides.export/markdownsaveoptions/showslidenumber) { get; set; } | Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non. La valeur par défaut est `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. Lecture/écriture Booléen. La valeur par défaut est **false**. |
| [SlideNumberFormat](../../aspose.slides.export/markdownsaveoptions/slidenumberformat) { get; set; } | Obtient ou définit la chaîne de format utilisée pour les en-têtes des numéros de diapositives dans la sortie Markdown. Le format doit inclure le placeholder "{0}", qui sera remplacé par l'index de la diapositive lors de l'exportation. Exemple : "# Slide {0}" produira "# Slide 1", "# Slide 2", etc. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions
    {
        ShowHiddenSlides = true,
        ShowSlideNumber = true,
        Flavor = Flavor.Github,
        ExportType = MarkdownExportType.Sequential,
        NewLineType = NewLineType.Windows
    };
    
    pres.Save("doc.md", new[] { 1, 2, 3, 4, 5, 6, 7, 8, 9 }, SaveFormat.Md, markdownSaveOptions);
}
```

### Voir aussi

* classe [SaveOptions](../saveoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
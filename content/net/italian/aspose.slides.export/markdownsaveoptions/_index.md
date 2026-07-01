---
title: MarkdownSaveOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta le opzioni che controllano come la presentazione deve essere salvata in markdown.
type: docs
weight: 4230
url: /it/aspose.slides.export/markdownsaveoptions/
---
## Classe MarkdownSaveOptions

Rappresenta le opzioni che controllano come la presentazione deve essere salvata in markdown.

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Costruttore. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BasePath](../../aspose.slides.export/markdownsaveoptions/basepath) { get; set; } | Specifica il percorso di base dove il documento con le risorse verrà salvato. Il valore predefinito è la directory corrente dell'applicazione. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Restituisce o imposta il font usato nel caso in cui il font sorgente non sia trovato. Lettura-scrittura String. |
| [ExportType](../../aspose.slides.export/markdownsaveoptions/exporttype) { get; set; } | Specifica la specifica markdown per convertire la presentazione. Il valore predefinito è `TextOnly`. |
| [Flavor](../../aspose.slides.export/markdownsaveoptions/flavor) { get; set; } | Specifica la specifica markdown per convertire la presentazione. Il valore predefinito è `Multi-markdown`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Restituisce o imposta lo stile visivo del gradiente. Lettura/scrittura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [HandleRepeatedSpaces](../../aspose.slides.export/markdownsaveoptions/handlerepeatedspaces) { get; set; } |  |
| [ImagesSaveFolderName](../../aspose.slides.export/markdownsaveoptions/imagessavefoldername) { get; set; } | Specifica il nome della cartella in cui salvare le immagini. Il valore predefinito è `Images`. |
| [NewLineType](../../aspose.slides.export/markdownsaveoptions/newlinetype) { get; set; } | Specifica se il documento generato deve avere nuove linee \\r(Macintosh) di \\n(Unix) o \\r\\n(Windows). Il valore predefinito è `Unix`. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedere [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RemoveEmptyLines](../../aspose.slides.export/markdownsaveoptions/removeemptylines) { get; set; } | Se impostato su `true`, rimuove le righe vuote o composte solo da spazi bianchi dall'output Markdown finale. Il valore predefinito è `false`. |
| [ShowComments](../../aspose.slides.export/markdownsaveoptions/showcomments) { get; set; } | Specifica se il documento generato deve mostrare i commenti o meno. Il valore predefinito è `false`. |
| [ShowHiddenSlides](../../aspose.slides.export/markdownsaveoptions/showhiddenslides) { get; set; } | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è `false`. |
| [ShowSlideNumber](../../aspose.slides.export/markdownsaveoptions/showslidenumber) { get; set; } | Specifica se il documento generato deve mostrare il numero di ciascuna diapositiva o meno. Il valore predefinito è `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura/scrittura Boolean. Il valore predefinito è **false**. |
| [SlideNumberFormat](../../aspose.slides.export/markdownsaveoptions/slidenumberformat) { get; set; } | Ottiene o imposta la stringa di formato usata per le intestazioni dei numeri di diapositiva nell'output Markdown. Il formato deve includere il segnaposto "{0}", che verrà sostituito con l'indice della diapositiva durante l'esportazione. Esempio: "# Slide {0}" produrrà "# Slide 1", "# Slide 2", ecc. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuare o essere interrotto. Lettura/scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Esempi

Esempio:

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

### Vedi anche

* classe [SaveOptions](../saveoptions)
* spazio dei nomi [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
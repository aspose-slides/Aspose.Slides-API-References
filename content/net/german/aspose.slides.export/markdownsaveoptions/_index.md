---
title: MarkdownSaveOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt Optionen dar, die steuern, wie Präsentationen in Markdown gespeichert werden sollen.
type: docs
weight: 4080
url: /de/aspose.slides.export/markdownsaveoptions/
---

## MarkdownSaveOptions-Klasse

Stellt Optionen dar, die steuern, wie Präsentationen in Markdown gespeichert werden sollen.

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Ctor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasePath](../../aspose.slides.export/markdownsaveoptions/basepath) { get; set; } | Gibt den Basis-Pfad an, unter dem das Dokument mit Ressourcen gespeichert wird. Standard ist das aktuelle Verzeichnis der Anwendung. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder setzt sie, die verwendet wird, falls die Quell-Schriftart nicht gefunden wird. Schreib-/lesbarer String. |
| [ExportType](../../aspose.slides.export/markdownsaveoptions/exporttype) { get; set; } | Gibt die Markdown-Spezifikation an, um die Präsentation zu konvertieren. Standard ist `TextOnly`. |
| [Flavor](../../aspose.slides.export/markdownsaveoptions/flavor) { get; set; } | Gibt die Markdown-Spezifikation an, um die Präsentation zu konvertieren. Standard ist `Multi-markdown`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Verlaufs zurück oder setzt ihn. Schreib-/lesbarer [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [HandleRepeatedSpaces](../../aspose.slides.export/markdownsaveoptions/handlerepeatedspaces) { get; set; } |  |
| [ImagesSaveFolderName](../../aspose.slides.export/markdownsaveoptions/imagessavefoldername) { get; set; } | Gibt den Ordnernamen an, unter dem Bilder gespeichert werden. Standard ist `Images`. |
| [NewLineType](../../aspose.slides.export/markdownsaveoptions/newlinetype) { get; set; } | Gibt an, ob das generierte Dokument Zeilenumbrüche \\r(Macintosh), \\n(Unix) oder \\r\\n(Windows) haben soll. Standard ist `Unix`. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für die Speicherung von Fortschrittsaktualisierungen in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RemoveEmptyLines](../../aspose.slides.export/markdownsaveoptions/removeemptylines) { get; set; } | Wenn auf `true` gesetzt, entfernt leere oder nur aus Leerzeichen bestehende Zeilen aus der endgültigen Markdown-Ausgabe. Standard ist `false`. |
| [ShowComments](../../aspose.slides.export/markdownsaveoptions/showcomments) { get; set; } | Gibt an, ob das generierte Dokument Kommentare anzeigen soll oder nicht. Standard ist `false`. |
| [ShowHiddenSlides](../../aspose.slides.export/markdownsaveoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [ShowSlideNumber](../../aspose.slides.export/markdownsaveoptions/showslidenumber) { get; set; } | Gibt an, ob das generierte Dokument die Nummer jeder Folie anzeigen soll oder nicht. Standard ist `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreib-/lesbarer Boolean. Der Standardwert ist **false**. |
| [SlideNumberFormat](../../aspose.slides.export/markdownsaveoptions/slidenumberformat) { get; set; } | Erhält oder setzt die Formatzeichenfolge, die für Foliennummernüberschriften in der Markdown-Ausgabe verwendet wird. Das Format muss den Platzhalter "{0}" enthalten, der während des Exports durch den Folienindex ersetzt wird. Beispiel: "# Folie {0}" ergibt "# Folie 1", "# Folie 2" usw. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder setzt es, das Warnungen erhält und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreib-/lesbarer [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Beispiele

Beispiel:

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

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
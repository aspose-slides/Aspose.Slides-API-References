---
title: HtmlOptions
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt HTMLExportoptionen dar.
type: docs
weight: 3590
url: /de/net/aspose.slides.export/htmloptions/
---
## HtmlOptions class

Stellt HTML-Exportoptionen dar.

```csharp
public class HtmlOptions : SaveOptions, IHtmlOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [HtmlOptions](htmloptions#constructor)() | Erstellt ein neues HtmlOptions-Objekt zum Speichern in einer einzigen HTML-Datei. |
| [HtmlOptions](htmloptions#constructor_1)(ILinkEmbedController) | Erstellt ein neues HtmlOptions-Objekt, das den Rückruf angibt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die verwendete Schriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird. Lesen/SchreibenString . |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/htmloptions/deletepicturescroppedareas) { get; set; } | Ein boolesches Flag gibt an, ob die abgeschnittenen Teile Teil des Dokuments bleiben. Wenn wahr, werden die abgeschnittenen Teile entfernt, wenn falsch, werden sie im Dokument serialisiert (was möglicherweise zu einer größeren Datei führen kann) |
| [HtmlFormatter](../../aspose.slides.export/htmloptions/htmlformatter) { get; set; } | Gibt die HTML-Vorlage zurück oder legt sie fest. Lesen/Schreiben[`IHtmlFormatter`](../ihtmlformatter) . |
| [JpegQuality](../../aspose.slides.export/htmloptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder legt einen Wert fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/SchreibenByte . |
| [NotesCommentsLayouting](../../aspose.slides.export/htmloptions/notescommentslayouting) { get; } | Bietet Optionen, die steuern, wie Notizen und Kommentare im exportierten Dokument platziert werden. |
| [PicturesCompression](../../aspose.slides.export/htmloptions/picturescompression) { get; set; } | Stellt die Komprimierungsstufe der Bilder dar |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Repräsentiert ein Callback-Objekt zum Speichern von Fortschrittsaktualisierungen in Prozent. Siehe[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [ShowHiddenSlides](../../aspose.slides.export/htmloptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument ausgeblendete Folien enthalten soll oder nicht. Standard ist`FALSCH` . |
| [SlideImageFormat](../../aspose.slides.export/htmloptions/slideimageformat) { get; set; } | Gibt Formatoptionen für Folienbilder zurück oder legt sie fest. Lesen/Schreiben[`ISlideImageFormat`](../islideimageformat) . |
| [SvgResponsiveLayout](../../aspose.slides.export/htmloptions/svgresponsivelayout) { get; set; } | True zum Ausschließen von Breiten- und Höhenattributen aus dem SVG-Container – das macht das Layout reaktionsfähig. Falsch – andernfalls. Lesen/SchreibenBoolean . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Siehe auch

* class [SaveOptions](../saveoptions)
* interface [IHtmlOptions](../ihtmloptions)
* namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
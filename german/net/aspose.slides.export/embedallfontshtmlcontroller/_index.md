---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides für .NET-API-Referenz
description: Die FormatierungsControllerKlasse die zum Einbetten aller Präsentationsschriftarten im WOFFFormat verwendet werden soll.
type: docs
weight: 3510
url: /de/net/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController class

Die Formatierungs-Controller-Klasse, die zum Einbetten aller Präsentationsschriftarten im WOFF-Format verwendet werden soll.

```csharp
public class EmbedAllFontsHtmlController : IHtmlFormattingController
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor)() | Erstellt eine neue Instanz |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor_1)(string[]) | Erstellt eine neue Instanz |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [WriteAllFonts](../../aspose.slides.export/embedallfontshtmlcontroller/writeallfonts)(IHtmlGenerator, IPresentation) | Schreiben Sie alle enthaltenen Schriftarten in[`Presentation`](../../aspose.slides/presentation) . |
| virtual [WriteDocumentEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentend)(IHtmlGenerator, IPresentation) | Wird aufgerufen, um die Fußzeile eines HTML-Dokuments zu schreiben. Einmal pro Präsentationskonvertierung aufgerufen. |
| virtual [WriteDocumentStart](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentstart)(IHtmlGenerator, IPresentation) | Wird aufgerufen, um den Header des HTML-Dokuments zu schreiben. Einmal pro Präsentationskonvertierung aufgerufen. |
| virtual [WriteFont](../../aspose.slides.export/embedallfontshtmlcontroller/writefont)(IHtmlGenerator, IFontData, IFontData, string, string, byte[]) | Schreibt Daten als base64 in das HTML-Dokument selbst |
| virtual [WriteShapeEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapeend)(IHtmlGenerator, IShape) | Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Diabildgenerierung abgeschlossen, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild wird über dem vorherigen gestartet. |
| virtual [WriteShapeStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapestart)(IHtmlGenerator, IShape) | Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Diabildgenerierung abgeschlossen, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild wird über dem vorherigen gestartet. |
| virtual [WriteSlideEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeslideend)(IHtmlGenerator, ISlide) | Aufruf zum Schreiben von HTML-Folienfußzeilen. Wird einmal pro Folie aufgerufen. |
| virtual [WriteSlideStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeslidestart)(IHtmlGenerator, ISlide) | Aufgerufen, um HTML-Folienkopfzeilen zu schreiben. Wird einmal pro Folie aufgerufen. |

### Siehe auch

* interface [IHtmlFormattingController](../ihtmlformattingcontroller)
* namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
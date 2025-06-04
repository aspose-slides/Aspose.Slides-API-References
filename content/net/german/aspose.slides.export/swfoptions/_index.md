---
title: SwfOptions
second_title: Aspose.Slides für .NET API Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.
type: docs
weight: 4340
url: /de/aspose.slides.export/swfoptions/
---

## SwfOptions-Klasse

Bietet Optionen, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SwfOptions](swfoptions)() | Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Gibt an, ob das generierte SWF-Dokument komprimiert werden soll oder nicht. Standard ist `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreibzeichenfolge. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Aktiviert/deaktiviert das Kontextmenü. Standard ist true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Verlaufs zurück oder legt ihn fest. Lese-/Schreib [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Gibt die Qualität der JPEG-Bilder an. Standard ist 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Bild, das in der oberen rechten Ecke des Betrachters als Logo angezeigt wird. Das Bild sollte ein PNG-Bild mit 32x64 Pixeln sein, andernfalls kann das Logo falsch angezeigt werden. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Ruft die vollständige Hyperlink-Adresse für ein Logo ab oder legt sie fest. Hat nur einen Effekt, wenn ein [`LogoImageBytes`](./logoimagebytes) angegeben ist. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Zeigt das untere Bedienfeld an/aus. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Zeigt die Schaltfläche für den Vollbildmodus an/aus. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Zeigt das linke Bedienfeld an/aus. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Gibt an, ob der Rahmen um die Seiten angezeigt werden soll. Standard ist true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Zeigt den Seitensteuerung an/aus. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Zeigt den Suchbereich an/aus. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Zeigt das gesamte obere Bedienfeld an/aus. Kann in flashvars überschrieben werden. Standard ist true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/Schreibboolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Exportieren einer Präsentation auf der Seite platziert werden [`ISlidesLayoutOptions`](../islideslayoutoptions). Diese Eigenschaft unterstützt nicht die Zuweisung von Objekten des Typs [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Beginnt mit geöffnetem linkem Bedienfeld. Kann in flashvars überschrieben werden. Der Standardwert ist false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Gibt an, ob das generierte SWF-Dokument den integrierten Dokumentenbetrachter enthalten soll oder nicht. Der Standardwert ist `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese-/Schreib [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Beispiele

Das folgende Beispiel zeigt, wie PowerPoint in SWF Flash konvertiert wird.

```csharp
[C#]
// Instanziieren Sie ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Präsentation und Notizenseiten speichern
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ISwfOptions](../iswfoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
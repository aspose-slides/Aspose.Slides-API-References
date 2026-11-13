---
title: SwfOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.
type: docs
weight: 4550
url: /de/aspose.slides.export/swfoptions/
---
## SwfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standard ist `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese-/Schreib-String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Aktiviert/Deaktiviert das Kontextmenü. Standard ist true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lese/Schreib [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Gibt die Qualität von JPEG-Bildern an. Standard ist 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Bild, das als Logo in der oberen rechten Ecke des Viewers angezeigt wird. Das Bild sollte ein 32 × 64-Pixel-PNG sein, sonst kann das Logo fehlerhaft dargestellt werden. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Gibt die vollständige Hyperlink-Adresse für ein Logo zurück oder legt sie fest. Wirksam nur, wenn ein [`LogoImageBytes`](./logoimagebytes) angegeben ist. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für Fortschritts-Updates beim Speichern in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Anzeige des unteren Bereichs ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Anzeige des Vollbild-Buttons ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standard ist `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Anzeige des linken Bereichs ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Gibt an, ob ein Rand um die Seiten angezeigt werden soll. Standard ist true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Anzeige des Seiten-Steppers ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Anzeige des Suchbereichs ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Anzeige des gesamten oberen Bereichs ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese/Schreib Boolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [`ISlidesLayoutOptions`](../islideslayoutoptions) auf der Seite angeordnet werden. Diese Eigenschaft unterstützt das Zuweisen von Objekten des Typs [`HandoutLayoutingOptions`](../handoutlayoutingoptions) nicht. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Startet mit geöffnetem linkem Bereich. Kann in flashvars überschrieben werden. Standard ist false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentviewer enthalten soll oder nicht. Standard ist `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese/Schreib [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Beispiele

Das folgende Beispiel zeigt, wie PowerPoint in SWF-Flash konvertiert wird.

```csharp
[C#]
// Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Speichern der Präsentation und Notizseiten
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ISwfOptions](../iswfoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
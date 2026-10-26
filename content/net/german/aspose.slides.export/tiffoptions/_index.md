---
title: TiffOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.
type: docs
weight: 4570
url: /de/aspose.slides.export/tiffoptions/
---
## Klasse TiffOptions

Stellt Optionen bereit, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TiffOptions](tiffoptions)() | Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Gibt den Algorithmus an, mit dem ein Farbbild in ein Schwarz-weiß-Bild umgewandelt wird. Diese Option wird nur angewendet, wenn [`CompressionType`](./compressiontype) auf CCITT4 oder CCITT3 gesetzt ist. Lesen/Schreiben [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Standardwert ist Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Gibt den Kompressionstyp an. Lesen/Schreiben [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, falls die Ausgangsschriftart nicht gefunden wird. Lesen/Schreiben String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Gibt die horizontale Auflösung in Punkten pro Zoll an. Lesen/Schreiben UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Gibt die vertikale Auflösung in Punkten pro Zoll an. Lesen/Schreiben UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Gibt die Größe eines erzeugten TIFF-Bildes an. Der Standardwert ist 0x0, was bedeutet, dass die Bildgrößen anhand der Größe der Präsentationsfolien berechnet werden. Lesen/Schreiben Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesen [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Gibt das Pixelformat für die erzeugten Bilder an. Lesen/Schreiben [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Rückruffunktionsobjekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen/Schreiben Boolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Gibt den Modus zurück oder legt ihn fest, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Beispiele

Das folgende Beispiel zeigt, wie PowerPoint mit Standardgröße in TIFF konvertiert wird.

```csharp
[C#]
// Ein Presentation-Objekt instanziieren, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Die Präsentation in ein TIFF-Dokument speichern
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Das folgende Beispiel zeigt, wie PowerPoint mit benutzerdefinierter Größe in TIFF konvertiert wird.

```csharp
[C#]
// Instanziert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instanziert die TiffOptions-Klasse
    TiffOptions opts = new TiffOptions();
    // Kompressionstyp festlegen
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Kompressionstypen
    // Default – Gibt das Standardschema für die Kompression an (LZW).
    // None – Gibt an, dass keine Kompression verwendet wird.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Die Tiefe hängt vom Kompressionstyp ab und kann nicht manuell gesetzt werden.
    // Auflösungseinheit ist immer gleich “2” (Punkte pro Zoll)
    // DPI des Bildes festlegen
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Bildgröße festlegen
    opts.ImageSize = new Size(1728, 1078);
    // Speichert die Präsentation als TIFF mit der angegebenen Bildgröße
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Das folgende Beispiel zeigt, wie PowerPoint mit benutzerdefiniertem Bild-Pixelformat in TIFF konvertiert wird.

```csharp
[C#]
// Instanziert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat enthält die folgenden Werte (wie aus der Dokumentation ersichtlich):
    Format1bppIndexed; // 1 Bit pro Pixel, indiziert.
    Format4bppIndexed; // 4 Bit pro Pixel, indiziert.
    Format8bppIndexed; // 8 Bit pro Pixel, indiziert.
    Format24bppRgb; // 24 Bit pro Pixel, RGB.
    Format32bppArgb; // 32 Bit pro Pixel, ARGB.
    */
    // Speichert die Präsentation als TIFF mit der angegebenen Bildgröße
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ITiffOptions](../itiffoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
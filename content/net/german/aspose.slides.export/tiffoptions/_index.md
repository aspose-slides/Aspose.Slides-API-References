---
title: TiffOptions
second_title: Aspose.Sildes für .NET API Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.
type: docs
weight: 4380
url: /de/aspose.slides.export/tiffoptions/
---

## TiffOptions-Klasse

Bietet Optionen, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.

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
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Gibt den Algorithmus zum Konvertieren eines Farbbildes in ein Schwarzweißbild an. Diese Option wird nur angewendet, wenn [`CompressionType`](./compressiontype) auf CCITT4 oder CCITT3 gesetzt ist. Lese-/schreibbar [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Standard ist Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Gibt den Kompressionstyp an. Lese-/schreibbar [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese-/schreibbarer String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Gibt die horizontale Auflösung in Punkten pro Zoll an. Lese-/schreibbar UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Gibt die vertikale Auflösung in Punkten pro Zoll an. Lese-/schreibbar UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Gradienten zurück oder legt ihn fest. Lese-/schreibbar [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Gibt die Größe eines generierten TIFF-Bildes an. Der Standardwert ist 0x0, was bedeutet, dass die generierten Bildgrößen basierend auf dem Wert der Präsentationsfolie berechnet werden. Lese-/schreibbar Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Gibt das Pixel-Format für die generierten Bilder an. Lese-/schreibbar [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für die Speicherung von Fortschrittsaktualisierungen in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/schreibbar Boolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Ruft den Modus ab oder legt ihn fest, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladeprozess fortgesetzt oder abgebrochen wird. Lese-/schreibbar [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Beispiele

Das folgende Beispiel zeigt, wie man PowerPoint in TIFF mit der Standardgröße konvertiert.

```csharp
[C#]
// Erstellen eines Presentation-Objekts, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Speichern der Präsentation im TIFF-Dokument
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Das folgende Beispiel zeigt, wie man PowerPoint in TIFF mit benutzerdefinierter Größe konvertiert.

```csharp
[C#]
// Erstellen eines Presentation-Objekts, das eine Präsentationsdatei darstellt
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Erstellen der TiffOptions-Klasse
    TiffOptions opts = new TiffOptions();
    // Setzen des Kompressionstyps
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Kompressionstypen
    // Default - Gibt das Standardkompressionsschema (LZW) an.
    // None - Gibt keine Kompression an.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Die Tiefe hängt vom Kompressionstyp ab und kann nicht manuell festgelegt werden.
    // Auflösungseinheit ist immer gleich “2” (Punkte pro Zoll)
    // Setzen der Bild-DPI
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Bildgröße festlegen
    opts.ImageSize = new Size(1728, 1078);
    // Speichern der Präsentation im TIFF mit der angegebenen Bildgröße
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Das folgende Beispiel zeigt, wie man PowerPoint in TIFF mit benutzerdefiniertem Bild-Pixel-Format konvertiert.

```csharp
[C#]
// Erstellen eines Presentation-Objekts, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat enthält die folgenden Werte (wie in der Dokumentation zu sehen):
    Format1bppIndexed; // 1 Bit pro Pixel, indiziert.
    Format4bppIndexed; // 4 Bits pro Pixel, indiziert.
    Format8bppIndexed; // 8 Bits pro Pixel, indiziert.
    Format24bppRgb; // 24 Bits pro Pixel, RGB.
    Format32bppArgb; // 32 Bits pro Pixel, ARGB.
    */
    // Speichern der Präsentation im TIFF mit dem angegebenen Bildformat
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ITiffOptions](../itiffoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
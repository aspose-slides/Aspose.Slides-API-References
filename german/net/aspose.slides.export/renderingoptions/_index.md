---
title: RenderingOptions
second_title: Aspose.Slides für .NET-API-Referenz
description: Bietet Optionen die steuern wie eine Präsentation/Folie gerendert wird.
type: docs
weight: 4000
url: /de/net/aspose.slides.export/renderingoptions/
---
## RenderingOptions class

Bietet Optionen, die steuern, wie eine Präsentation/Folie gerendert wird.

```csharp
public class RenderingOptions : SaveOptions, IRenderingOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [RenderingOptions](renderingoptions)() | Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die verwendete Schriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird. Lesen/SchreibenString . |
| [NotesCommentsLayouting](../../aspose.slides.export/renderingoptions/notescommentslayouting) { get; } | Bietet Optionen, die steuern, wie Notizen und Kommentare im exportierten Dokument platziert werden. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Repräsentiert ein Callback-Objekt zum Speichern von Fortschrittsaktualisierungen in Prozent. Siehe[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
  {
  IRenderingOptions renderingOpts = new RenderingOptions();
  renderingOpts.NotesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
  
  pres.Slides[0].GetThumbnail(renderingOpts).Save("pres-Original.png", ImageFormat.Png);
  
  renderingOpts.DefaultRegularFont = "Arial Black";
  pres.Slides[0].GetThumbnail(renderingOpts).Save("pres-ArialBlackDefault.png", ImageFormat.Png);
  
  renderingOpts.DefaultRegularFont = "Arial Narrow";
  pres.Slides[0].GetThumbnail(renderingOpts).Save("pres-ArialNarrowDefault.png", ImageFormat.Png);
}
```

### Siehe auch

* class [SaveOptions](../saveoptions)
* interface [IRenderingOptions](../irenderingoptions)
* namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
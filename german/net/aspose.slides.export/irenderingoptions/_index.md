---
title: IRenderingOptions
second_title: Aspose.Slides für .NET-API-Referenz
description: Bietet Optionen die steuern wie eine Präsentation/Folie gerendert wird.
type: docs
weight: 3730
url: /de/net/aspose.slides.export/irenderingoptions/
---
## IRenderingOptions interface

Bietet Optionen, die steuern, wie eine Präsentation/Folie gerendert wird.

```csharp
public interface IRenderingOptions : ISaveOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/irenderingoptions/asisaveoptions) { get; } | Gibt die ISaveOptions-Schnittstelle zurück. Schreibgeschützt[`ISaveOptions`](../isaveoptions) . |
| [NotesCommentsLayouting](../../aspose.slides.export/irenderingoptions/notescommentslayouting) { get; } | Bietet Optionen, die steuern, wie Notizen und Kommentare im exportierten Dokument platziert werden. |

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

* interface [ISaveOptions](../isaveoptions)
* namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
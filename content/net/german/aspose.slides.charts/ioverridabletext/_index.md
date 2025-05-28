---
title: IOverridableText
second_title: Aspose.Slides für .NET API Referenz
description: Stellt überschreibbaren Text für ein Diagramm dar.
type: docs
weight: 2100
url: /de/aspose.slides.charts/ioverridabletext/
---

## IOverridableText-Schnittstelle

Stellt überschreibbaren Text für ein Diagramm dar.

```csharp
public interface IOverridableText : IFormattedTextContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ioverridabletext/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-IFormattedTextContainer-Schnittstelle. Nur lesbar [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [TextFrameForOverriding](../../aspose.slides.charts/ioverridabletext/textframeforoverriding) { get; } | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text. Automatisch generierter Text ist eine implizite Eigenschaft der Datenbeschriftung, der Anzeigeeinheit des Werteachse, des Achsentitels, des Diagrammtitels und der Beschriftung der Trendlinie. Automatisch generierter Text wird mit der IFormattedTextContainer.TextFormat-Eigenschaft formatiert. Nur lesbar [`ITextFrame`](../../aspose.slides/itextframe). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/ioverridabletext/addtextframeforoverriding)(string) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach den Text. |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->
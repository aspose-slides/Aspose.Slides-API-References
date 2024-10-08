---
title: IHyperlink
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt einen Hyperlink dar.
type: docs
weight: 5600
url: /de/aspose.slides/ihyperlink/
---
## IHyperlink interface

Stellt einen Hyperlink dar.

```csharp
public interface IHyperlink
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActionType](../../aspose.slides/ihyperlink/actiontype) { get; } | Gibt den Aktionstyp von HyperLinkEx zurück. Schreibgeschützt[`HyperlinkActionType`](../hyperlinkactiontype) . |
| [ColorSource](../../aspose.slides/ihyperlink/colorsource) { get; set; } | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Teilformat. Lesen/Schreiben[`HyperlinkColorSource`](../hyperlinkcolorsource) . |
| [ExternalUrl](../../aspose.slides/ihyperlink/externalurl) { get; } | Gibt die externe URL an. Wenn diese Eigenschaft nicht null wird, wird die Eigenschaft TargetSlide null. SchreibgeschütztString . |
| [HighlightClick](../../aspose.slides/ihyperlink/highlightclick) { get; set; } | Legt fest, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lesen/SchreibenBoolean . |
| [History](../../aspose.slides/ihyperlink/history) { get; set; } | Legt fest, ob das Ziel des übergeordneten Hyperlinks beim Aufrufen zu einer Liste der angezeigten Hyperlinks hinzugefügt werden soll. Lesen/SchreibenBoolean . |
| [StopSoundOnClick](../../aspose.slides/ihyperlink/stopsoundonclick) { get; set; } | Legt fest, ob der Ton beim Klicken auf einen Hyperlink gestoppt werden soll. Lesen/SchreibenBoolean . |
| [TargetFrame](../../aspose.slides/ihyperlink/targetframe) { get; set; } | Gibt den Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, sofern vorhanden. Lesen/SchreibenString . |
| [TargetSlide](../../aspose.slides/ihyperlink/targetslide) { get; } | Wenn HyperlinkEx auf eine bestimmte Folie abzielt, wird diese Folie zurückgegeben. Wenn die Eigenschaft nicht null wird, wird die Eigenschaft ExternalUrl null. Schreibgeschützt[`ISlide`](../islide) . |
| [Tooltip](../../aspose.slides/ihyperlink/tooltip) { get; set; } | Gibt die Zeichenfolge zurück, die in einer Benutzerschnittstelle angezeigt werden kann, die mit dem übergeordneten Hyperlink verknüpft ist. Lesen/SchreibenString . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../aspose.slides/ihyperlink/equals)(IHyperlink) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |

### Siehe auch

* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

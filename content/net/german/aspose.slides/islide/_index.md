---
title: ISlide
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Folie in einer Präsentation dar.
type: docs
weight: 6820
url: /de/aspose.slides/islide/
---

## ISlide-Schnittstelle

Stellt eine Folie in einer Präsentation dar.

```csharp
public interface ISlide : IBaseSlide, IOverrideThemeable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIBaseSlide](../../aspose.slides/islide/asibaseslide) { get; } | Ermöglicht den Zugriff auf die Basis-IBaseSlide-Schnittstelle. Nur-lesbar [`IBaseSlide`](../ibaseslide). |
| [AsIOverrideThemeable](../../aspose.slides/islide/asioverridethemeable) { get; } | Gibt die IOverrideThemeable-Schnittstelle zurück. Nur-lesbar [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [HeaderFooterManager](../../aspose.slides/islide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Folie zurück. Nur-lesbar [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/islide/hidden) { get; set; } | Bestimmt, ob die angegebene Folie während einer Diashow verborgen ist. Lese-/Schreibbare Boolean. |
| [LayoutSlide](../../aspose.slides/islide/layoutslide) { get; set; } | Gibt die Layout-Folie für die aktuelle Folie zurück oder legt sie fest. Lese-/Schreibbare [`ILayoutSlide`](../ilayoutslide). |
| [NotesSlideManager](../../aspose.slides/islide/notesslidemanager) { get; } | Ermöglicht den Zugriff auf die Notizfolie, fügt sie hinzu und entfernt sie. Nur-lesbar [`INotesSlideManager`](../inotesslidemanager). |
| [SlideNumber](../../aspose.slides/islide/slidenumber) { get; set; } | Gibt die Foliennummer zurück. Der Index der Folie in der [`Slides`](../ipresentation/slides)-Sammlung ist immer gleich SlideNumber - 1. Lese-/Schreibbare Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetImage](../../aspose.slides/islide/getimage#getimage)() | Gibt ein Thumbnail-Bildobjekt (20% der tatsächlichen Größe) zurück. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_1)(IRenderingOptions) | Gibt ein Thumbnail-Bitmapobjekt zurück. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_4)(ITiffOptions) | Gibt ein Thumbnail-TIFF-Bitmapobjekt mit den angegebenen Parametern zurück. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_6)(Size) | Gibt ein Bildobjekt mit der angegebenen Größe zurück. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_5)(float, float) | Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_3)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bitmapobjekt mit der angegebenen Größe zurück. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_2)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bitmapobjekt mit benutzerdefinierter Skalierung zurück. |
| [GetSlideComments](../../aspose.slides/islide/getslidecomments)(ICommentAuthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| [Remove](../../aspose.slides/islide/remove)() | Entfernt die Folie aus der Präsentation. |
| [Reset](../../aspose.slides/islide/reset)() | Setzt die Position, Größe und Formatierung jeder Form zurück, die ein Prototyp auf LayoutSlide hat. |
| [WriteAsEmf](../../aspose.slides/islide/writeasemf)(Stream) | Speichert den Folieninhalt als EMF-Datei. |
| [WriteAsSvg](../../aspose.slides/islide/writeassvg#writeassvg)(Stream) | Speichert den Folieninhalt als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/islide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Folieninhalt als SVG-Datei. |

### Siehe Auch

* Schnittstelle [IBaseSlide](../ibaseslide)
* Schnittstelle [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
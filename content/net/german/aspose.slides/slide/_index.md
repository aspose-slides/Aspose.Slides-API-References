---
title: Slide
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Folie in einer Präsentation dar.
type: docs
weight: 9980
url: /de/aspose.slides/slide/
---
## Slide Klasse

Stellt eine Folie in einer Präsentation dar.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Nur lesend [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Nur lesend [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesend [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Folie zurück. Nur lesend [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Bestimmt, ob die angegebene Folie während einer Diashow ausgeblendet ist. Lese-/Schreib Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesend [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Gibt das Layout der aktuellen Folie zurück oder legt es fest. Lese-/Schreib [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder legt ihn fest. Lese-/Schreib String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Ermöglicht den Zugriff auf die Notizfolie, das Hinzufügen und Entfernen. Nur lesend [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Nur lesend [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Nur lesend [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lese-/Schreib Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Nur lesend UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Gibt die Nummer einer Folie zurück. Der Index einer Folie in der [`Slides`](../presentation/slides)-Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lese-/Schreib Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Diashow weitergeht. Nur lesend [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Gibt den überschreibenden Theme-Manager zurück. Nur lesend [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animations-Zeitlinienobjekt zurück. Nur lesend [`IAnimationTimeLine`](../ianimationtimeline). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Theme für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht die eindeutigen Bezeichnerwerte, z. B. SlideId, und dynamische Inhalte, z. B. den aktuellen Datumswert im Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Gibt ein Thumbnail-Image-Objekt (20 % der Originalgröße) zurück. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Gibt ein Thumbnail-Image-Objekt zurück. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Gibt ein Thumbnail-Tiff-Bildobjekt mit angegebenen Parametern zurück. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [Remove](../../aspose.slides/slide/remove)() | Entfernt die Folie aus der Präsentation. |
| [Reset](../../aspose.slides/slide/reset)() | Setzt Position, Größe und Formatierung jeder Form zurück, die ein Prototyp auf LayoutSlide hat. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Speichert den Folieninhalt als EMF-Datei. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Speichert den Folieninhalt als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Folieninhalt als SVG-Datei. |

### Siehe auch

* Klasse [BaseSlide](../baseslide)
* Schnittstelle [ISlide](../islide)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
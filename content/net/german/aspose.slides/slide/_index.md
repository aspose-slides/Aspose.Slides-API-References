---
title: Slide
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert eine Folie in einer Präsentation.
type: docs
weight: 9210
url: /de/aspose.slides/slide/
---
## Slide class

Repräsentiert eine Folie in einer Präsentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Schreibgeschützt[`IBackground`](../ibackground) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Schreibgeschützt[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Folie zurück. Schreibgeschützt[`ISlideHeaderFooterManager`](../islideheaderfootermanager) . |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Bestimmt, ob die angegebene Folie während einer Diashow ausgeblendet wird. Lesen/SchreibenBoolean . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Schreibgeschützt[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Gibt das Folienlayout für die aktuelle Folie zurück oder legt es fest. Lesen/Schreiben[`ILayoutSlide`](../ilayoutslide) . |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder legt ihn fest. Lesen/SchreibenString . |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Zugriff auf die Notizenfolie zulassen, hinzufügen und entfernen. Schreibgeschützt[`INotesSlideManager`](../inotesslidemanager) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Schreibgeschützt[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lesen/SchreibenBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. SchreibgeschütztUInt32 . |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Gibt eine Nummer der Folie zurück. Index der Folie in[`Slides`](../presentation/slides) Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lesen/SchreibenInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Übergangsobjekt zurück, das Informationen über enthält, wie die angegebene Folie während einer Diashow vorrückt. Schreibgeschützt[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Gibt den übergeordneten Themenmanager zurück. Schreibgeschützt[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitachsenobjekt zurück. Schreibgeschützt[`IAnimationTimeLine`](../ianimationtimeline) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Design für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen gleich sind. usw. sind gleich. Der Vergleich berücksichtigt keine eindeutigen Kennungswerte, z. B. SlideId und dynamische Inhalte, z. B. aktueller Datumswert in Datumsplatzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail)() | Gibt ein Thumbnail Image-Objekt zurück (20 % der tatsächlichen Größe). |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_4)(IRenderingOptions) | Gibt ein Thumbnail-Bitmap-Objekt zurück. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_7)(ITiffOptions) | Gibt ein Thumbnail-Tiff-Bitmap-Objekt mit angegebenen Parametern zurück. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_9)(Size) | Gibt ein Thumbnail-Bitmap-Objekt mit angegebener Größe zurück. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_8)(float, float) | Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_6)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bitmap-Objekt mit angegebener Größe zurück. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_5)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |
| [Remove](../../aspose.slides/slide/remove)() | Entfernt Folie aus Präsentation. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_3)(IRenderingOptions, Graphics) | Rendert eine bestimmte Folie in ein Grafikobjekt. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_5)(IRenderingOptions, Graphics, Size) | Rendert eine bestimmte Folie in einem Grafikobjekt unter Verwendung der angegebenen Größe. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_4)(IRenderingOptions, Graphics, float, float) | Rendert bestimmte Folien in ein Grafikobjekt mit benutzerdefinierter Skalierung. |
| [Reset](../../aspose.slides/slide/reset)() | Setzt Position, Größe und Formatierung jeder Form zurück, die einen Prototyp auf LayoutSlide hat. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Speichert den Inhalt der Folie als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt der Folie als SVG-Datei. |

### Siehe auch

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

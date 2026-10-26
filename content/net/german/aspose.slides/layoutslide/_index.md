---
title: LayoutSlide
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Layoutfolie dar.
type: docs
weight: 7640
url: /de/aspose.slides/layoutslide/
---
## LayoutSlide Klasse

Stellt eine Layoutfolie dar.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Nur lesbar [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung der ActiveX-Steuerelemente auf einer Folie zurück. Nur lesbar [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Gibt eine Sammlung von Zeichenhilfslinien für die Layoutfolie zurück. Nur lesbar [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Gibt true zurück, wenn mindestens eine Folie von dieser Layoutfolie abhängt. Nur lesbar Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Layoutfolie zurück. Nur lesbar [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesbar [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Gibt den Layouttyp dieser Layoutfolie zurück. Nur lesbar [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Gibt die Masterfolie für ein Layout zurück oder legt sie fest. Lesen/Schreiben [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder legt ihn fest. Lesen/Schreiben String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Gibt den Platzhalter-Manager der Layoutfolie zurück. Nur lesbar [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Nur lesbar [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. Lesen/Schreiben Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Nur lesbar UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Diashow fortschreitet. Nur lesbar [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Gibt den überschreibenden Theme-Manager zurück. Nur lesbar [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitlinien-Objekt zurück. Nur lesbar [`IAnimationTimeLine`](../ianimationtimeline). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Theme für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur der Folie und statischem Inhalt berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht eindeutige Bezeichnerwerte, z. B. SlideId, und dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Layoutfolie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Läufe mit derselben Formatierung in allen Absätzen aller zulässigen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen zulässigen Formen. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Entfernt das Layout aus der Präsentation. |

### Siehe auch

* Klasse [BaseSlide](../baseslide)
* Schnittstelle [ILayoutSlide](../ilayoutslide)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: LayoutSlide
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Layoutfolie dar.
type: docs
weight: 6970
url: /de/aspose.slides/layoutslide/
---
## LayoutSlide class

Stellt eine Layoutfolie dar.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Schreibgeschützt[`IBackground`](../ibackground) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Schreibgeschützt[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Gibt wahr zurück, wenn es mindestens eine Folie gibt, die von dieser Layoutfolie abhängt. SchreibgeschütztBoolean . |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Layoutfolie zurück. Schreibgeschützt[`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Schreibgeschützt[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Gibt den Layouttyp dieser Layoutfolie zurück. Schreibgeschützt[`SlideLayoutType`](../slidelayouttype) . |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Gibt die Masterfolie für ein Layout zurück oder legt sie fest. Lesen/Schreiben[`IMasterSlide`](../imasterslide) . |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder legt ihn fest. Lesen/SchreibenString . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Schreibgeschützt[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lesen/SchreibenBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. SchreibgeschütztUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Übergangsobjekt zurück, das Informationen über enthält, wie die angegebene Folie während einer Diashow vorrückt. Schreibgeschützt[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Gibt den übergeordneten Themenmanager zurück. Schreibgeschützt[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitachsenobjekt zurück. Schreibgeschützt[`IAnimationTimeLine`](../ianimationtimeline) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Design für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen gleich sind. usw. sind gleich. Der Vergleich berücksichtigt keine eindeutigen Kennungswerte, z. B. SlideId und dynamische Inhalte, z. B. aktueller Datumswert in Datumsplatzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Layoutfolie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Läufe mit gleicher Formatierung in allen Absätzen alle akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Entfernt das Layout aus der Präsentation. |

### Siehe auch

* class [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

---
title: LayoutSlide
second_title: Aspose.Slides für .NET API Referenz
description: Stellt einen Layout-Folie dar.
type: docs
weight: 7400
url: /de/aspose.slides/layoutslide/
---

## LayoutSlide Klasse

Stellt eine Layout-Folie dar.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Nur lesbar [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Nur lesbar [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Gibt true zurück, wenn mindestens eine Folie existiert, die von dieser Layout-Folie abhängt. Nur lesbar Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Gibt den Header-Footer-Manager der Layout-Folie zurück. Nur lesbar [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesbar [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Gibt den Layout-Typ dieser Layout-Folie zurück. Nur lesbar [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Gibt die Master-Folie für ein Layout zurück oder legt sie fest. Lese-/Schreibzugriff [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder legt ihn fest. Lese-/Schreibzugriff String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Gibt den Platzhalter-Manager der Layout-Folie zurück. Nur lesbar [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt das IPresentation-Interface zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Nur lesbar [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Master-Folie auf Folien angezeigt werden sollen oder nicht. Lese-/Schreibzugriff Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Nur lesbar UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Übergangsobjekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Diashow voranschreitet. Nur lesbar [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Gibt den übergeordneten Themenmanager zurück. Nur lesbar [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animations-Zeitplanobjekt zurück. Nur lesbar [`IAnimationTimeLine`](../ianimationtimeline). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Thema für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht die Werte eindeutiger Identifikatoren, z. B. SlideId, und dynamische Inhalte, z. B. den aktuellen Datumswert im Platzhalter für das Datum. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet die erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Layout-Folie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Absätze mit demselben Format in allen Absätzen aller akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Absätze mit demselben Format in allen Absätzen in allen akzeptablen Formen. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Entfernt das Layout aus der Präsentation. |

### Siehe auch

* Klasse [BaseSlide](../baseslide)
* Schnittstelle [ILayoutSlide](../ilayoutslide)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: MasterSlide
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt eine Masterfolie in einer Präsentation dar.
type: docs
weight: 8030
url: /de/aspose.slides/masterslide/
---
## MasterSlide Klasse

Repäsentiert eine Masterfolie in einer Präsentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Nur lesbar [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Gibt den Stil eines Fließtextes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück. Nur lesbar [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. Nur lesbar [`IDrawingGuidesCollection`](../idrawingguidescollection). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. Nur lesbar Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Masterfolie zurück. Nur lesbar [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Ermöglicht einfachen Zugriff auf enthaltene Hyperlinks. Nur lesbar [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Gibt die Sammlung von untergeordneten Layout-Folien für diese Masterfolie zurück. Nur lesbar [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Gibt den Namen einer Masterfolie zurück oder legt ihn fest. Lese-/Schreibzugriff String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Gibt den Stil eines anderen Textes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Bestimmt, ob die zugehörige Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht werden. Hinweis: Aspose.Slides entfernt niemals eigenständig ungenutzte Masterfolien; um ungenutzte Masterfolien tatsächlich zu entfernen, rufen Sie [`RemoveUnused`](../masterslidecollection/removeunused) auf. Lese-/Schreibzugriff Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Nur lesbar [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück. Lese-/Schreibzugriff Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Nur lesbar UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Vorführung fortschreitet. Nur lesbar [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Gibt den Theme-Manager zurück. Nur lesbar [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitlinien-Objekt zurück. Nur lesbar [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Gibt den Stil eines Titeltextes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Theme für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datumsplatzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Runs mit derselben Formatierung in allen Absätzen aller akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Runs mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |

### Siehe auch

* Klasse [BaseSlide](../baseslide)
* Schnittstelle [IMasterSlide](../imasterslide)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
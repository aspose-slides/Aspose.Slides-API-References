---
title: MasterSlide
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Masterfolie in einer Präsentation dar.
type: docs
weight: 8050
url: /de/aspose.slides/masterslide/
---
## MasterSlide Klasse

Stellt eine Masterfolie in einer Präsentation dar.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Schreibgeschützt [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Gibt den Stil eines Fließtextes zurück. Schreibgeschützt [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung der ActiveX-Steuerelemente auf einer Folie zurück. Schreibgeschützt [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Schreibgeschützt [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Gibt eine Sammlung von Zeichenhilfen für die Masterfolie zurück. Schreibgeschützt [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Gibt true zurück, wenn mindestens eine Folie von dieser Masterfolie abhängt. Schreibgeschützt Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Masterfolie zurück. Schreibgeschützt [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Schreibgeschützt [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Gibt die Sammlung der untergeordneten Layoutfolien für diese Masterfolie zurück. Schreibgeschützt [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Gibt den Namen einer Masterfolie zurück oder setzt ihn. Lese-/Schreibzugriff String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Gibt den Stil eines anderen Textes zurück. Schreibgeschützt [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Schreibgeschützt [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Legt fest, ob die zugehörige Masterfolie gelöscht wird, wenn alle Folien, die dieser Masterfolie folgen, gelöscht sind. Hinweis: Aspose.Slides entfernt niemals automatisch unbenutzte Masterfolien; um unbenutzte Masterfolien tatsächlich zu entfernen, rufen Sie [`RemoveUnused`](../masterslidecollection/removeunused) auf. Lese-/Schreibzugriff Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Schreibgeschützt [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück. Lese-/Schreibzugriff Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Schreibgeschützt UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Diashow fortschreitet. Schreibgeschützt [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Gibt den Theme-Manager zurück. Schreibgeschützt [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitlinien-Objekt zurück. Schreibgeschützt [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Gibt den Stil eines Titeltexts zurück. Schreibgeschützt [`ITextStyle`](../itextstyle). |

## Methoden

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Theme darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Theme für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und weitere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht eindeutige Bezeichnerwerte, z. B. SlideId, und dynamische Inhalte, z. B. den aktuellen Datumswert im Datums-Platzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Fügt Läufe mit gleicher Formatierung in allen Absätzen aller akzeptablen Formen zusammen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Fügt Läufe mit gleicher Formatierung in allen Absätzen in allen akzeptablen Formen zusammen. |

### Siehe auch

* Klasse [BaseSlide](../baseslide)
* Schnittstelle [IMasterSlide](../imasterslide)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
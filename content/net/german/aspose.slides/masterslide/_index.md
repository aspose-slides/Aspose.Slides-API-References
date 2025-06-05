---
title: MasterSlide
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Masterfolie in einer Präsentation dar.
type: docs
weight: 7780
url: /de/aspose.slides/masterslide/
---

## MasterSlide-Klasse

Stellt eine Masterfolie in einer Präsentation dar.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Nur lesbar [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Gibt den Stil eines Fließtextes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Nur lesbar [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Gibt true zurück, wenn mindestens eine Folie existiert, die von dieser Masterfolie abhängt. Nur lesbar Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Masterfolie zurück. Nur lesbar [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesbar [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Gibt die Sammlung der untergeordneten Layoutfolien für diese Masterfolie zurück. Nur lesbar [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Gibt den Namen einer Masterfolie zurück oder setzt ihn. Lese-/Schreib-String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Gibt den Stil eines anderen Textes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Bestimmt, ob das entsprechende Master gelöscht wird, wenn alle Folien, die diesem Master folgen, gelöscht werden. Hinweis: Aspose.Slides wird niemals ungenutzte Master von sich aus entfernen. Um tatsächlich ungenutzte Master zu entfernen, rufen Sie [`RemoveUnused`](../masterslidecollection/removeunused) auf. Lese-/Schreib-Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Nur lesbar [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer `false` zurück. Lese-/Schreib-Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Nur lesbar UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Übergangsobjekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Diashow fortschreitet. Nur lesbar [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Gibt den Themen-Manager zurück. Nur lesbar [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitstrahlobjekt zurück. Nur lesbar [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Gibt den Stil eines Titeltextes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Erstellt eine neue Masterfolie basierend auf der aktuellen und wendet ein externes Thema darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Thema für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und anderen Einstellungen etc. gleich sind. Die Vergleichsmethode berücksichtigt keine eindeutigen Identifikatoren, z.B. SlideId, und dynamische Inhalte, z.B. den aktuellen Datumswert im Datumsplatzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Abschnitte mit derselben Formatierung in allen Absätzen aller akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Abschnitte mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |

### Siehe auch

* Klasse [BaseSlide](../baseslide)
* Schnittstelle [IMasterSlide](../imasterslide)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
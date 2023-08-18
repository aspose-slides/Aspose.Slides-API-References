---
title: MasterSlide
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Masterfolie in einer Präsentation dar.
type: docs
weight: 7350
url: /de/aspose.slides/masterslide/
---
## MasterSlide class

Stellt eine Masterfolie in einer Präsentation dar.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Schreibgeschützt[`IBackground`](../ibackground) . |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Gibt den Stil eines Fließtextes zurück. Schreibgeschützt[`ITextStyle`](../itextstyle) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Schreibgeschützt[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Gibt „true“ zurück, wenn mindestens eine Folie vorhanden ist, die von dieser Masterfolie abhängt. SchreibgeschütztBoolean . |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Masterfolie zurück. Schreibgeschützt[`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Schreibgeschützt[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Gibt die Sammlung untergeordneter Layoutfolien für diese Masterfolie zurück. Schreibgeschützt[`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection) . |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Gibt den Namen einer Masterfolie zurück oder legt ihn fest. Lesen/SchreibenString . |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Gibt den Stil eines anderen Textes zurück. Schreibgeschützt[`ITextStyle`](../itextstyle) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Legt fest, ob der entsprechende Master gelöscht wird, wenn alle Folien, die diesem Master folgen, gelöscht werden. Hinweis: Aspose.Slides wird niemals unbenutzte Master selbst entfernen, um tatsächlich unbenutzte Master zu entfernen[`RemoveUnused`](../masterslidecollection/removeunused) Lesen/SchreibenBoolean . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Schreibgeschützt[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer zurück`FALSCH` . Lesen/SchreibenBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. SchreibgeschütztUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Übergangsobjekt zurück, das Informationen über enthält, wie die angegebene Folie während einer Diashow vorrückt. Schreibgeschützt[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Gibt den Themenmanager zurück. Schreibgeschützt[`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitachsenobjekt zurück. Schreibgeschützt[`IAnimationTimeLine`](../ianimationtimeline) . |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Gibt den Stil eines Titeltextes zurück. Schreibgeschützt[`ITextStyle`](../itextstyle) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Erstellt eine neue Masterfolie basierend auf der aktuellen, wendet ein externes Design darauf an und wendet die erstellte Masterfolie auf alle abhängigen Folien an. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Design für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen gleich sind. usw. sind gleich. Der Vergleich berücksichtigt keine eindeutigen Kennungswerte, z. B. SlideId und dynamische Inhalte, z. B. aktueller Datumswert in Datumsplatzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Gibt ein Array mit allen Folien zurück, die von dieser Masterfolie abhängen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Läufe mit gleicher Formatierung in allen Absätzen alle akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |

### Siehe auch

* class [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

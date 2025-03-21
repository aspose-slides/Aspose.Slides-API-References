---
title: NotesSlide
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Notizenfolie in einer Präsentation dar.
type: docs
weight: 8440
url: /de/aspose.slides/notesslide/
---
## NotesSlide class

Stellt eine Notizenfolie in einer Präsentation dar.

```csharp
public class NotesSlide : BaseSlide, INotesSlide
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Schreibgeschützt[`IBackground`](../ibackground) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Schreibgeschützt[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [HeaderFooterManager](../../aspose.slides/notesslide/headerfootermanager) { get; } | Gibt HeaderFooter-Manager der Notizenfolie zurück. Schreibgeschützt[`INotesSlideHeaderFooterManager`](../inotesslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Schreibgeschützt[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder legt ihn fest. Lesen/SchreibenString . |
| [NotesTextFrame](../../aspose.slides/notesslide/notestextframe) { get; } | Gibt einen TextFrame mit Notizentext zurück, falls vorhanden. Schreibgeschützt[`ITextFrame`](../itextframe) . |
| [ParentSlide](../../aspose.slides/notesslide/parentslide) { get; } | Gibt die übergeordnete Folie zurück. Schreibgeschützt[`ISlide`](../islide) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Schreibgeschützt[`IPresentation`](../ipresentation) . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Schreibgeschützt[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/notesslide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lesen/SchreibenBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. SchreibgeschütztUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Übergangsobjekt zurück, das Informationen über enthält, wie die angegebene Folie während einer Diashow vorrückt. Schreibgeschützt[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/notesslide/thememanager) { get; } | Gibt den übergeordneten Themenmanager zurück. Schreibgeschützt[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animationszeitachsenobjekt zurück. Schreibgeschützt[`IAnimationTimeLine`](../ianimationtimeline) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Design für diese Folie zurück. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen gleich sind. usw. sind gleich. Der Vergleich berücksichtigt keine eindeutigen Kennungswerte, z. B. SlideId und dynamische Inhalte, z. B. aktueller Datumswert in Datumsplatzhalter. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet das erste Vorkommen einer Form mit dem angegebenen alternativen Text. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Verbindet Läufe mit gleicher Formatierung in allen Absätzen alle akzeptablen Formen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |

### Siehe auch

* class [BaseSlide](../baseslide)
* interface [INotesSlide](../inotesslide)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

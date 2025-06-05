---  
title: Slide
second_title: Aspose.Slides für .NET API Referenz  
description: Stellt eine Folie in einer Präsentation dar.
type: docs
weight: 9650  
url: /de/aspose.slides/slide/
---  

## Slide-Klasse  

Stellt eine Folie in einer Präsentation dar.  

```csharp  
public sealed class Slide : BaseSlide, ISlide  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [Background](../../aspose.slides/baseslide/background) { get; } | Gibt den Hintergrund der Folie zurück. Nur lesbar [`IBackground`](../ibackground). |  
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Gibt die Sammlung der ActiveX-Steuerelemente auf einer Folie zurück. Nur lesbar [`IControlCollection`](../icontrolcollection). |  
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [`ICustomData`](../icustomdata). |  
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Folie zurück. Nur lesbar [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |  
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Bestimmt, ob die angegebene Folie während einer Diashow verborgen ist. Lese-/Schreib-Boolean. |  
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesbar [`IHyperlinkQueries`](../ihyperlinkqueries). |  
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Gibt die Layoutfolie für die aktuelle Folie zurück oder setzt sie. Lese-/Schreib [`ILayoutSlide`](../ilayoutslide). |  
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Gibt den Namen einer Folie zurück oder setzt ihn. Lese-/Schreib-String. |  
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Ermöglicht den Zugriff auf die Notizfolie, fügt diese hinzu und entfernt sie. Nur lesbar [`INotesSlideManager`](../inotesslidemanager). |  
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Gibt die IPresentation-Schnittstelle zurück. Nur lesbar [`IPresentation`](../ipresentation). |  
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Gibt die Formen einer Folie zurück. Nur lesbar [`IShapeCollection`](../ishapecollection). |  
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lese-/Schreib-Boolean. |  
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Gibt die ID einer Folie zurück. Nur lesbar UInt32. |  
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Gibt die Nummer der Folie zurück. Der Index der Folie in der [`Slides`](../presentation/slides) Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lese-/Schreib-Int32. |  
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Gibt das Transition-Objekt zurück, welches Informationen darüber enthält, wie die angegebene Folie während einer Diashow voranschreitet. Nur lesbar [`ISlideShowTransition`](../islideshowtransition). |  
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Gibt den übergeordneten Themenmanager zurück. Nur lesbar [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |  
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Gibt das Animations-Zeitplanobjekt zurück. Nur lesbar [`IAnimationTimeLine`](../ianimationtimeline). |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Gibt ein effektives Thema für diese Folie zurück. |  
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird auf Basis der Struktur und des statischen Inhalts der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine Werte von eindeutigen Identifikatoren, z.B. SlideId und dynamischen Inhalten, z.B. aktuellen Datumswert im Datumsplatzhalter. |  
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Findet die erste Vorkommen einer Form mit dem angegebenen alternativen Text. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Gibt ein Thumbnail-Bildobjekt (20 % der tatsächlichen Größe) zurück. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Gibt ein Thumbnail-Bildobjekt zurück. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Gibt ein Thumbnail-Tiff-Bildobjekt mit den angegebenen Parametern zurück. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Gibt ein Thumbnail-Bildobjekt mit der angegebenen Größe zurück. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Gibt ein Thumbnail-Bildobjekt mit benutzerdefinierter Skalierung zurück. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bildobjekt mit der angegebenen Größe zurück. |  
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bildobjekt mit benutzerdefinierter Skalierung zurück. |  
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |  
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Verbindet Abschnitte mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |  
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Verbindet Abschnitte mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen. |  
| [Remove](../../aspose.slides/slide/remove)() | Entfernt die Folie aus der Präsentation. |  
| [Reset](../../aspose.slides/slide/reset)() | Setzt Position, Größe und Formatierung jeder Form zurück, die ein Prototyp auf der Layoutfolie hat. |  
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Speichert den Folieninhalt als EMF-Datei. |  
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Speichert den Folieninhalt als SVG-Datei. |  
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Folieninhalt als SVG-Datei. |  

### Siehe auch  

* Klasse [BaseSlide](../baseslide)  
* Schnittstelle [ISlide](../islide)  
* Namespace [Aspose.Slides](../../aspose.slides)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
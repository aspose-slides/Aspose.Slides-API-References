---
title: SummaryZoomSection
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Rahmen dar.
type: docs
weight: 10470
url: /de/aspose.slides/summaryzoomsection/
---

## SummaryZoomSection-Klasse

Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Rahmen dar.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzeichenfolge. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzeichenfolge. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft, die angibt, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen an der Form zurück. Schreibgeschützter Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Schreibgeschütztes [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Gibt die textuelle Beschreibung des Summary Zoom Section-Objekts zurück. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: Kann für bestimmte Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Schreibgeschütztes [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Schreibgeschütztes [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen einer Form zurück oder setzt sie. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschütztes [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibwert. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form versteckt ist. Lese-/Schreibboolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Schreibgeschütztes [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouse Over definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Holt oder setzt den Bildtyp eines Zoom-Objekts. Lese-/Schreib [`ZoomImageType`](../zoomimagetype). Standardwert: Vorschau |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option „Als dekorativ markieren“. Lese-/Schreibboolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Schreibgeschützter Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Schreibgeschützter Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linie-Formatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Formen, die keine Linieneigenschaften haben, null zurückgeben. Schreibgeschütztes [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Muss nicht null sein. Verwenden Sie bei Bedarf einen leeren String-Wert. Lese-/Schreibzeichenfolge. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Identifikationsnummer der Form im Folienscope. Schreibgeschützter UInt32. Siehe auch [`UniqueId`](../shape/uniqueid), um die eindeutige Identifikationsnummer der Form im Präsentationsscope zu erhalten. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Schreibgeschütztes [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Schreibgeschütztes [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Schreibgeschütztes [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmens einer Form zurück oder setzt sie. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Holt oder setzt das Navigationsverhalten in der Slideshow. Lese-/Schreibboolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die Z-Achse rotiert ist. Ein positiver Wert gibt eine Drehung im Uhrzeigersinn an; ein negativer Wert gibt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibwert. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschütztes [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Holt oder setzt den Wert, der angibt, ob der Zoom den Hintergrund der Zielfolie verwenden soll. Lese-/Schreibboolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Schreibgeschütztes [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Holt oder setzt das Abschnittsobjekt, mit dem das Section Zoom-Objekt verknüpft ist. Lese-/Schreib [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Schreibgeschütztes [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Gibt den textuellen Titel des Summary Zoom Section-Objekts zurück. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Holt oder setzt die Dauer der Übergangs zwischen Zoom und Folie. Lese-/Schreibwert. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Identifikationsnummer der Form im Präsentationsscope. Schreibgeschützter UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid), um die eindeutige Identifikationsnummer der Form im Folienscope zu erhalten. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibwert. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibwert. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibwert. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Holt oder setzt das Bild für das Zoom-Objekt. Lese-/Schreib [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form an, die sich ganz hinten in der Z-Reihenfolge befindet, und Shapes[Shapes.Count - 1] gibt die Form an, die sich ganz vorne in der Z-Reihenfolge befindet. Schreibgeschützter Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls noch keiner vorhanden ist, und setzt die Eigenschaften des Platzhalters auf einen bestimmten Wert. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von der Layout- und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [SectionZoomFrame](../sectionzoomframe)
* Schnittstelle [ISummaryZoomSection](../isummaryzoomsection)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
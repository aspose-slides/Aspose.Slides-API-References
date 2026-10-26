---
title: SummaryZoomSection
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Frame dar.
type: docs
weight: 10780
url: /de/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection Klasse

Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Frame dar.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Liefert oder legt den alternativen Text fest, der einer shape zugeordnet ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Liefert oder legt den Titel des alternativen Textes fest, der einer shape zugeordnet ist. Lesen/Schreiben String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine shape im Schwarz-Weiß-Anzeigemodus gerendert wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Liefert die Anzahl der Verbindungspunkte der shape. Nur Lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Liefert die benutzerdefinierten Daten der shape. Nur Lesen [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Liefert die Textbeschreibung des Summary Zoom Section-Objekts. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Liefert das EffectFormat-Objekt, das Pixeleffekte enthält, die auf eine shape angewendet wurden. Hinweis: Kann null zurückgeben für bestimmte Formen, die keine Effekt-Eigenschaften besitzen. Nur Lesen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Liefert das FillFormat-Objekt, das Füllformatierungs-Eigenschaften für eine shape enthält. Hinweis: Kann null zurückgeben für bestimmte Formen, die keine Füll-Eigenschaften besitzen. Nur Lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Liefert oder legt die Eigenschaften des shape-Frames fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Liefert die Sperren der shape. Nur Lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Liefert oder legt die Höhe der shape fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die shape ausgeblendet ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Liefert oder legt den für Mausklick definierten Hyperlink fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Liefert den Hyperlink-Manager. Nur Lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Liefert oder legt den für Maus-Über definierten Hyperlink fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Liefert oder legt den Bildtyp eines Zoom-Objekts fest. Lesen/Schreiben [`ZoomImageType`](../zoomimagetype). Standardwert: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Liefert oder legt die Option 'Mark as decorative' fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die shape gruppiert ist. Nur Lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die shape ein TextHolder_PPT ist. Nur Lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Liefert das LineFormat-Objekt, das Linienformatierungseigenschaften für eine shape enthält. Hinweis: Kann null zurückgeben für bestimmte Formen, die keine Linien-Eigenschaften besitzen. Nur Lesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Liefert oder legt den Namen einer shape fest. Darf nicht null sein. Bei Bedarf leere Zeichenkette verwenden. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Liefert einen eindeutigen Identifier, der nur für die Folie gilt und während der Lebensdauer der shape konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die shape von überall im Dokument zuverlässig zu referenzieren. Nur Lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Liefert das übergeordnete GroupShape-Objekt, wenn die shape gruppiert ist. Andernfalls null. Nur Lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Liefert den Platzhalter einer shape. Gibt null zurück, wenn die shape keinen Platzhalter hat. Nur Lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Liefert die übergeordnete Präsentation einer Folie. Nur Lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Liefert oder legt die rohen Eigenschaften des shape-Frames fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Liefert oder legt das Navigationsverhalten in der Diashow fest. Lesen/Schreiben Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Liefert oder legt die Anzahl der Grad fest, um die die angegebene shape um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Gegen-Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Liefert die Sperren der shape. Nur Lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Liefert oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Ziel-Folien verwendet. Lesen/Schreiben Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Liefert die übergeordnete Folie einer shape. Nur Lesen [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Liefert oder legt das Abschnittsobjekt fest, auf das das Section Zoom-Objekt verweist. Lesen/Schreiben [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Liefert das ThreeDFormat-Objekt, das 3D-Effekteigenschaften für eine shape enthält. Hinweis: Kann null zurückgeben für bestimmte Formen, die keine 3D-Eigenschaften besitzen. Nur Lesen [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Liefert den Texttitel des Summary Zoom Section-Objekts. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Liefert oder legt die Dauer des Übergangs zwischen Zoom und Folie fest. Lesen/Schreiben Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Liefert einen internen, präsentationsbezogenen Identifier, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, muss er nicht als dauerhafter eindeutiger Schlüssel behandelt werden. Nur Lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Liefert oder legt die Breite der shape fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Liefert oder legt die X-Koordinate der oberen linken Ecke der shape fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Liefert oder legt die Y-Koordinate der oberen linken Ecke der shape fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Liefert oder legt das Bild für das Zoom-Objekt fest. Lesen/Schreiben [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Liefert die Position einer shape in der Z-Reihenfolge. Shapes[0] liefert die shape am hinteren Ende der Z-Reihenfolge, und Shapes[Shapes.Count - 1] liefert die shape am vorderen Ende. Nur Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt die Platzhalter-Eigenschaften auf einen angegebenen fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Liefert eine grundlegende Platzhalter-shape (shape aus dem Layout und/oder der Master-Folien, von der die aktuelle shape ererbt wird). Null wird zurückgegeben, wenn die aktuelle shape nicht ererbt wird. |
| [GetImage](../../aspose.slides/shape/getimage)() | Liefert das Shape-Thumbnail. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Liefert das Shape-Thumbnail. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Liefert die visuellen Grenzen der shape, berechnet aus ihrem gerenderten Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese shape kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Shape als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Shape als SVG-Datei. |

### Siehe auch

* Klasse [SectionZoomFrame](../sectionzoomframe)
* Schnittstelle [ISummaryZoomSection](../isummaryzoomsection)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
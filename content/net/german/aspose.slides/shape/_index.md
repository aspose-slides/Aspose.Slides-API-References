---
title: Shape
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein Shape auf einer Folie dar.
type: docs
weight: 9850
url: /de/aspose.slides/shape/
---
## Shape Klasse

Stellt ein Shape auf einer Folie dar.

```csharp
public class Shape : IShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn für ein Shape fest. Lese/Schreib String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt ihn für ein Shape fest. Lese/Schreib String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft bestimmt, wie ein Shape im Schwarz-Weiß-Anzeige-Modus gerendert wird. Lese/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte des Shapes zurück. Nur lesbar Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten des Shapes zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf ein Shape angewendet werden. Hinweis: Kann null zurückgeben für bestimmte Shape-Typen, die keine Effekt-Eigenschaften besitzen. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften für ein Shape enthält. Hinweis: Kann null zurückgeben für bestimmte Shape-Typen, die keine Füll-Eigenschaften besitzen. Nur lesbar [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Shape-Frames zurück oder setzt sie. Lese/Schreib [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe des Shapes zurück oder setzt sie, gemessen in Punkten. Lese/Schreib Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob das Shape ausgeblendet ist. Lese/Schreib Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lese/Schreib [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouse-Over definierten Hyperlink zurück oder setzt ihn. Lese/Schreib [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder setzt sie. Lese/Schreib Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob das Shape gruppiert ist. Nur lesbar Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob das Shape TextHolder_PPT ist. Nur lesbar Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformat-Eigenschaften für ein Shape enthält. Hinweis: Kann null zurückgeben für bestimmte Shape-Typen, die keine Linien-Eigenschaften besitzen. Nur lesbar [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen eines Shapes zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lese/Schreib String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der für die Lebensdauer des Shapes konstant bleibt und PowerPoint oder Interop-Code ermöglicht, das Shape zuverlässig von überall im Dokument zu referenzieren. Nur lesbar UInt32. Siehe auch [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn das Shape gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für ein Shape zurück. Gibt null zurück, wenn das Shape keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Shape-Frames zurück oder setzt sie. Lese/Schreib [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Gradzahl zurück oder setzt sie, um das angegebene Shape um die Z-Achse zu drehen. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Gegen-Uhrzeigersinn. Lese/Schreib Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Gibt die Sperren des Shapes zurück. Nur lesbar [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie eines Shapes zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für ein Shape enthält. Hinweis: Kann null zurückgeben für bestimmte Shape-Typen, die keine 3D-Eigenschaften besitzen. Nur lesbar [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhafter eindeutiger Schlüssel behandelt werden. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite des Shapes zurück oder setzt sie, gemessen in Punkten. Lese/Schreib Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke des Shapes zurück oder setzt sie, gemessen in Punkten. Lese/Schreib Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke des Shapes zurück oder setzt sie, gemessen in Punkten. Lese/Schreib Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position eines Shapes in der Z-Reihenfolge zurück. Shapes[0] liefert das Shape ganz hinten in der Z-Reihenfolge, und Shapes[Shapes.Count - 1] liefert das Shape ganz vorne. Nur lesbar Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt ein grundlegendes Platzhalter-Shape zurück (Shape aus dem Layout und/oder der Master-Folie, von dem das aktuelle Shape ererbt wird). Es wird null zurückgegeben, wenn das aktuelle Shape nicht vererbt wird. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Gibt das Shape-Miniaturbild zurück. Der Typ ShapeThumbnailBounds.Shape für die Miniaturbild-Grenzen wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Gibt das Shape-Miniaturbild zurück. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ermittelt die visuellen Grenzen des Shapes, berechnet aus dessen gerendertem Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass dieses Shape kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt des Shapes als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt des Shapes als SVG-Datei. |

### Siehe auch

* Schnittstelle [IShape](../ishape)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
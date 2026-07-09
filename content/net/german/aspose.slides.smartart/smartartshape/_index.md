---
title: SmartArtShape
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein SmartArt Shape dar
type: docs
weight: 10660
url: /de/aspose.slides.smartart/smartartshape/
---
## SmartArtShape Klasse

Stellt ein SmartArt-Shape dar

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten des Shapes zurück. Nur lesbar [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Liefert oder legt den alternativen Text eines Shapes fest. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Liefert oder legt den Titel des alternativen Textes eines Shapes fest. Lesen/Schreiben String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie ein Shape im Schwarz-weiß-Anzeige-Modus gerendert wird. Lesen/Schreiben [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte des Shapes zurück. Nur lesbar Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten des Shapes zurück. Nur lesbar [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf das Shape angewendet werden. Hinweis: kann null zurückgeben für bestimmte Shape-Typen, die keine Effekt-Eigenschaften besitzen. Nur lesbar [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für ein Shape enthält. Hinweis: kann null zurückgeben für bestimmte Shape-Typen, die keine Füll-Eigenschaften besitzen. Nur lesbar [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Liefert oder legt die Eigenschaften des Shape-Frames fest. Lesen/Schreiben [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Liefert oder legt die Höhe des Shapes in Punkten fest. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob das Shape verborgen ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Liefert oder legt den für Mausklick definierten Hyperlink fest. Lesen/Schreiben [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Liefert oder legt den für Maus-over definierten Hyperlink fest. Lesen/Schreiben [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Liefert oder legt die Option 'Mark as decorative' fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob das Shape gruppiert ist. Nur lesbar Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob das Shape TextHolder_PPT ist. Nur lesbar Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für ein Shape enthält. Hinweis: kann null zurückgeben für bestimmte Shape-Typen, die keine Linien-Eigenschaften besitzen. Nur lesbar [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Liefert oder legt den Namen eines Shapes fest. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer des Shapes konstant bleibt und PowerPoint oder Interop-Code ermöglicht, das Shape zuverlässig von überall im Dokument zu referenzieren. Nur lesbar UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn das Shape gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für ein Shape zurück. Gibt null zurück, wenn das Shape keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Liefert oder legt die Roh-Eigenschaften des Shape-Frames fest. Lesen/Schreiben [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Liefert oder legt die Drehung des angegebenen Shapes um die Z-Achse in Grad fest. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Gibt die Sperren des Shapes zurück. Nur lesbar [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Style-Objekt des Shapes zurück. Nur lesbar [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Liefert oder legt den vordefinierten Geometrie-Typ fest. Hinweis: Bei Änderung des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen/Schreiben [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie eines Shapes zurück. Nur lesbar [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Gibt den Text des SmartArt-Shapes zurück. Nur lesbar [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für ein Shape enthält. Hinweis: kann null zurückgeben für bestimmte Shape-Typen, die keine 3D-Eigenschaften besitzen. Nur lesbar [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel verwendet werden. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Liefert oder legt die Breite des Shapes in Punkten fest. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Liefert oder legt die X-Koordinate der oberen linken Ecke des Shapes in Punkten fest. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Liefert oder legt die Y-Koordinate der oberen linken Ecke des Shapes in Punkten fest. Lesen/Schreiben Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position eines Shapes in der Z-Reihenfolge zurück. Shapes[0] liefert das Shape ganz hinten in der Z-Reihenfolge, und Shapes[Shapes.Count - 1] liefert das Shape ganz vorne. Nur lesbar Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array von Shape-Elementen zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt ein grundlegendes Platzhalter-Shape zurück (Shape aus dem Layout und/oder der Master-Folien, von dem das aktuelle Shape erbt). Null wird zurückgegeben, wenn das aktuelle Shape nicht erbt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt eine Kopie des Pfads des Geometrie-Shapes zurück. Koordinaten sind relativ zur linken oberen Ecke des Shapes. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Shape-Thumbnail zurück. Der ShapeThumbnailBounds.Shape-Typ für Thumbnail-Grenzen wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds,float,float) | Gibt das Shape-Thumbnail zurück. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ermittelt die visuellen Grenzen des Shapes, basierend auf dessen gerendertem Inhalt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass dieses Shape kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Shape-Geometrie aus dem [`IGeometryPath`](../../aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke des Shapes sein. Ändert den Typ des Shapes ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) zu Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Shape-Geometrie aus einem Array von [`IGeometryPath`](../../aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken oberen Ecke des Shapes sein. Ändert den Typ des Shapes ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) zu Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt des Shapes als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream,ISVGOptions) | Speichert den Inhalt des Shapes als SVG-Datei. |

### Siehe auch

* Klasse [GeometryShape](../../aspose.slides/geometryshape)
* Schnittstelle [ISmartArtShape](../ismartartshape)
* Namensraum [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
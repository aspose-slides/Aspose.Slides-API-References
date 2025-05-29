---
title: Connector
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt einen Connector dar.
type: docs
weight: 2580
url: /de/aspose.slides/connector/
---

## Connector-Klasse

Stellt einen Connector dar.

```csharp
public class Connector : GeometryShape, IConnector
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten des Shapes zurück. Nur lesbar [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einem Shape verknüpft ist. Lese-/schreibbar String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder legt ihn fest, der mit einem Shape verknüpft ist. Lese-/schreibbar String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie ein Shape im Schwarz-Weiß-Displaymodus dargestellt wird. Lese-/schreibbar [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte am Shape zurück. Nur lesbar Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Gibt die Locks des Connectors zurück. Nur lesbar [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten des Shapes zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf ein Shape angewendet werden. Hinweis: kann null für bestimmte Typen von Shapes zurückgeben, die keine Effekt-Eigenschaften haben. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Gibt das Shape zurück oder legt es fest, an das das Ende des Connectors angeschlossen werden soll. Lese-/schreibbar [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Gibt den Index des Verbindungspunktes für das End-Shape zurück oder legt ihn fest. Lese-/schreibbar UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für ein Shape enthält. Hinweis: kann null für bestimmte Typen von Shapes zurückgeben, die keine Füll-Eigenschaften haben. Nur lesbar [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Shape-Rahmens zurück oder legt sie fest. Lese-/schreibbar [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe des Shapes zurück oder legt sie fest. Lese-/schreibbar Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob das Shape versteckt ist. Lese-/schreibbar Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/schreibbar [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/schreibbar [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder legt sie fest. Lese-/schreibbar Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob das Shape gruppiert ist. Nur lesbar Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob das Shape ein TextHolder_PPT ist. Nur lesbar Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für ein Shape enthält. Hinweis: kann null für bestimmte Typen von Shapes zurückgeben, die keine Linien-Eigenschaften haben. Nur lesbar [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen eines Shapes zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie leere Zeichenfolge, wenn nötig. Lese-/schreibbar String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt eine eindeutige Shape-ID im Folienkontext zurück. Nur lesbar UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zur Ermittlung der eindeutigen Shape-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn das Shape gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für ein Shape zurück. Gibt null zurück, wenn das Shape keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Roh-Shape-Rahmens zurück oder legt sie fest. Lese-/schreibbar [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die das angegebene Shape um die Z-Achse rotiert ist. Ein positiver Wert zeigt eine Uhrzeigerrichtung an; ein negativer Wert zeigt eine gegen den Uhrzeigersinn gerichtete Rotation an. Lese-/schreibbar Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Gibt die Locks des Shapes zurück. Nur lesbar [`IConnectorLock`](../iconnectorlock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Style-Objekt des Shapes zurück. Nur lesbar [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Gibt den AutoShape-Typ zurück oder legt ihn fest. Lese-/schreibbar [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie eines Shapes zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Gibt das Shape zurück oder legt es fest, an das der Anfang des Connectors angeschlossen werden soll. Lese-/schreibbar [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Gibt den Index des Verbindungspunktes für das Start-Shape zurück oder legt ihn fest. Lese-/schreibbar UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für ein Shape enthält. Hinweis: kann null für bestimmte Typen von Shapes zurückgeben, die keine 3D-Eigenschaften haben. Nur lesbar [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Shape-ID im Präsentationskontext zurück. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zur Ermittlung der eindeutigen Shape-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite des Shapes zurück oder legt sie fest. Lese-/schreibbar Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke des Shapes zurück oder legt sie fest. Lese-/schreibbar Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke des Shapes zurück oder legt sie fest. Lese-/schreibbar Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position eines Shapes in der Z-Reihenfolge zurück. Shapes[0] gibt das Shape an, das sich hinten in der Z-Reihenfolge befindet, und Shapes[Shapes.Count - 1] gibt das Shape an, das sich vorne in der Z-Reihenfolge befindet. Nur lesbar Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Platzhaltereigenschaften auf die angegebenen fest. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Elemente des Shapes zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt ein grundlegendes Platzhalter-Shape zurück (Shape aus dem Layout und/oder der Master-Folie, von dem das aktuelle Shape abgeleitet ist). Ein null wird zurückgegeben, wenn das aktuelle Shape nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt eine Kopie des Pfades des Geometrie-Speichers zurück. Die Koordinaten beziehen sich auf die obere linke Ecke des Shapes. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild des Shapes zurück. Der Typ ShapeThumbnailBounds.Shape für die Miniaturbildgrenzen wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild des Shapes zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass dieses Shape kein Platzhalter ist. |
| [Reroute](../../aspose.slides/connector/reroute)() | Leitet den Connector um, sodass er den kürzesten möglichen Weg zwischen den Shapes nimmt, die er verbindet. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Formgeometrie aus dem [`IGeometryPath`](../igeometrypath)-Objekt. Die Koordinaten müssen relativ zur oberen linken Ecke des Shapes sein. Ändert den Typ des Shapes ([`ShapeType`](../geometryshape/shapetype)) in Benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur oberen linken Ecke des Shapes sein. Ändert den Typ des Shapes ([`ShapeType`](../geometryshape/shapetype)) in Benutzerdefiniert. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt des Shapes als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt des Shapes als SVG-Datei. |

### Siehe auch

* Klasse [GeometryShape](../geometryshape)
* Schnittstelle [IConnector](../iconnector)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
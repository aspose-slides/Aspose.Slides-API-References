---
title: GeometryShape
second_title: Aspose.Slides für .NET API Referenz
description: Stellt die Elternklasse für alle geometrischen Formen dar.
type: docs
weight: 4770
url: /de/aspose.slides/geometryshape/
---

## GeometryShape-Klasse

Stellt die Elternklasse für alle geometrischen Formen dar.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung der Anpassungswerte der Form zurück. Nur lesbar [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Darstellungsmodus dargestellt wird.. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur lesbar Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewendeten Pixel-Effekte enthält. Hinweis: kann für bestimmte Formen, die keine Effekteigenschaften haben, null zurückgeben. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften einer Form enthält. Hinweis: kann für bestimmte Formen, die keine Füllungseigenschaften haben, null zurückgeben. Nur lesbar [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Füllrahmens der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für das Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ruft die Option "Als dekorativ kennzeichnen" ab oder legt sie fest. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesbar Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur lesbar Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Liniendaten haben, null zurückgeben. Nur lesbar [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Muss nicht null sein. Verwenden Sie bei Bedarf den leeren String. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft die eindeutige Form-ID im Folienbereich ab. Nur lesbar UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen der eindeutigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert gibt eine Drehung im Uhrzeigersinn an; ein negativer Wert gibt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stil-Objekt der Form zurück. Nur lesbar [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Gibt den Geometrie-Voreinstellungstyp zurück oder legt ihn fest. Hinweis: Bei Wertänderungen werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lese-/Schreibzugriff [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekteigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur lesbar [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft die eindeutige Form-ID im Präsentationsbereich ab. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Folienbereich. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der Z-Reihenfolge zurück. Nur lesbar Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und setzt die Platzhaltereigenschaften auf die angegebene. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Elemente der Form zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhaltersform zurück (Form von dem Layout und/oder Masterfolien, von der die aktuelle Form stammt). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt die Kopie des Pfades der geometrischen Form zurück. Die Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Thumbnail der Form zurück. ShapeThumbnailBounds.Shape-Typ wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Thumbnail der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](../igeometrypath)-Objekt. Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](./shapetype)) in Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](./shapetype)) in Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [Shape](../shape)
* Schnittstelle [IGeometryShape](../igeometryshape)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
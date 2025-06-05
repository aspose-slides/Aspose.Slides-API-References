---
title: SmartArtShape
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine SmartArt-Form dar
type: docs
weight: 10350
url: /de/aspose.slides.smartart/smartartshape/
---

## SmartArtShape-Klasse

Stellt eine SmartArt-Form dar

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur lesend [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den Alternativtext zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese- und schreibbar String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des Alternativtexts zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese- und schreibbar String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese- und schreibbar [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur lesend Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesend [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewendeten Pixeleffekte enthält. Hinweis: kann für bestimmte Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur lesend [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungs-Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur lesend [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder legt sie fest. Lese- und schreibbar [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese- und schreibbar Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese- und schreibbar Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese- und schreibbar [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesend [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese- und schreibbar [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ruft die 'Als dekorativ markieren'-Option ab oder legt sie fest. Lese- und schreibbar Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesend Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur lesend Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Linien-Eigenschaften haben, null zurückgeben. Nur lesend [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie bei Bedarf den leeren String. Lese- und schreibbar String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft die eindeutige Form-ID im Folienkontext ab. Nur lesend UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) zum Abrufen der eindeutigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls null. Nur lesend [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesend [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesend [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmens der Form zurück oder legt sie fest. Lese- und schreibbar [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Uhrzeigersinn-Rotation an; ein negativer Wert zeigt eine Gegenuhrzeigersinn-Rotation an. Lese- und schreibbar Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesend [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Nur lesend [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Gibt den Geometrie-Voreinstellungstyp zurück oder legt ihn fest. Hinweis: Bei einer Änderungswertsetzung werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lese- und schreibbar [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesend [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Gibt den Text der SmartArt-Form zurück. Nur lesend [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur lesend [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft die eindeutige Form-ID im Präsentationskontext ab. Nur lesend UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese- und schreibbar Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese- und schreibbar Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese- und schreibbar Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form zurück, die sich ganz hinten in der Z-Reihenfolge befindet, und Shapes[Shapes.Count - 1] gibt die Form zurück, die sich ganz vorne in der Z-Reihenfolge befindet. Nur lesend Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Platzhaltereigenschaften auf einen bestimmten Wert fest. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Elemente der Form zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von der Layout- und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Eine null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt eine Kopie des Pfades der geometrischen Form zurück. Die Koordinaten beziehen sich auf die obere linke Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. ShapeThumbnailBounds.Shape-Form-Miniaturansicht-Grenze wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Formgeometrie aus dem [`IGeometryPath`](../../aspose.slides/igeometrypath)-Objekt. Die Koordinaten müssen sich auf die obere linke Ecke der Form beziehen. Ändert den Typ der Form ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) auf Benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](../../aspose.slides/igeometrypath). Die Koordinaten müssen sich auf die obere linke Ecke der Form beziehen. Ändert den Typ der Form ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) auf Benutzerdefiniert. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GeometryShape](../../aspose.slides/geometryshape)
* Schnittstelle [ISmartArtShape](../ismartartshape)
* Namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
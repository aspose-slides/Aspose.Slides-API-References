---
title: AutoShape
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine AutoShape dar.
type: docs
weight: 820
url: /de/aspose.slides/autoshape/
---

## AutoShape-Klasse

Stellt eine AutoShape dar.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur lesbar [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff auf String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff auf String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Gibt die Sperren der AutoShape zurück. Nur lesbar [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Displaymodus dargestellt wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur lesbar Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewendeten Pixeleffekte enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Effekteigenschaften haben. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungs Eigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Füll Eigenschaften haben. Nur lesbar [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff auf Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für die Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option 'Als dekorativ kennzeichnen' Lese-/Schreibzugriff auf Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesbar Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Gibt an, ob die Form eine Textbox ist. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur lesbar Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungs Eigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Linien Eigenschaften haben. Nur lesbar [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie den leeren String, wenn nötig. Lese-/Schreibzugriff auf String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt den eindeutigen Identifikator der Form im Folienkontext. Nur lesbar UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen des eindeutigen Identifikators der Form im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Rohdaten des Formrahmens zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff auf Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesbar [`IAutoShapeLock`](../iautoshapelock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Nur lesbar [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Gibt den oder legt den geometrischen Voreinstellungstyp fest. Hinweis: Bei Wertänderungen werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lese-/Schreibzugriff [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Gibt das TextFrame-Objekt für die AutoShape zurück. Nur lesbar [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt Eigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur lesbar [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt den eindeutigen Identifikator der Form im Präsentationskontext. Nur lesbar UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen des eindeutigen Identifikators der Form im Folienkontext. |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Bestimmt, ob diese AutoShape mit der Hintergrundfüllung der Folie anstelle des durch den Stil oder das Füllformat angegebenen gefüllt werden soll. Lese-/Schreibzugriff auf Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form im Z-Ordnung zurück. Shapes[0] gibt die Form ganz hinten im Z-Ordnung zurück, und Shapes[Shapes.Count - 1] gibt die Form ganz vorne im Z-Ordnung zurück. Nur lesbar Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt die Platzhaltereigenschaften auf einen bestimmten Wert fest. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Fügt einer Form ein neues TextFrame hinzu. Wenn die Form bereits ein TextFrame hat, ändert sie einfach dessen Text. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array der Elemente der Form zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form erbt). Ein null wird zurückgegeben, wenn die aktuelle Form nicht vererbt wird. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt eine Kopie des Pfades der geometrischen Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](../igeometrypath) Objekt. Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf benutzerdefiniert. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GeometryShape](../geometryshape)
* Schnittstelle [IAutoShape](../iautoshape)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: AutoShape
second_title: Aspose.Sildes für .NET API-Referenz
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur-Lesen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verbunden ist. Lese-/Schreibzugriff auf String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verbunden ist. Lese-/Schreibzugriff auf String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Gibt die Sperren der AutoShape zurück. Nur-Lesen [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus dargestellt wird. Lese-/Schreibzugriff auf [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur-Lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: kann für bestimmte Formen, die keine Effekteigenschaften haben, null zurückgeben. Nur-Lesen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungs Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Fülleigenschaften haben, null zurückgeben. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lese-/Schreibzugriff auf Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff auf [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff auf [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Erhält oder legt die Option „Als dekorativ markieren“ fest. Lese-/Schreibzugriff auf Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesen Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Gibt an, ob die Form ein Textfeld ist. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungs Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Linienspezifikationen haben, null zurückgeben. Nur-Lesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie leeren String-Wert, wenn nötig. Lese-/Schreibzugriff auf String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ermöglicht den Zugriff auf die eindeutige Formkennung im Folienkontext. Nur-Lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für den Abruf der eindeutigen Formkennung im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter einer Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Rahmens einer Form zurück oder legt sie fest. Lese-/Schreibzugriff auf [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff auf Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IAutoShapeLock`](../iautoshapelock). (2 Eigenschaften) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Gibt das Stilobjekt der Form zurück. Nur-Lesen [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Gibt den Geometrievoreinstellungstyp zurück oder legt ihn fest. Hinweis: Bei Änderung des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lese-/Schreibzugriff auf [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lesen [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Gibt das TextFrame-Objekt für die AutoShape zurück. Nur-Lesen [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-Lesen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ermöglicht den Zugriff auf die eindeutige Formkennung im Präsentationskontext. Nur-Lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für den Abruf der eindeutigen Formkennung im Folienkontext. |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Bestimmt, ob diese AutoShape mit der Hintergrundfüllung der Folie gefüllt werden soll, anstatt mit der durch den Stil oder das Füllformat angegebenen. Lese-/Schreibzugriff auf Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff auf Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Reihenfolge zurück. Nur-Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und legt die Eigenschaften des Platzhalters auf einen bestimmten fest. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Fügt eine neue TextFrame zu einer Form hinzu. Wenn die Form bereits ein TextFrame hat, wird einfach der Text geändert. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Erstellt und gibt ein Array von Formelementen zurück. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Ein null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Gibt eine Kopie des Pfades der Geometrieform zurück. Die Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. ShapeThumbnailBounds.Shape Miniaturbildgrenzen-Typ wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualisiert die Formgeometrie aus dem [`IGeometryPath`](../igeometrypath)-Objekt. Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf benutzerdefiniert. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](../igeometrypath). Die Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../geometryshape/shapetype)) auf benutzerdefiniert. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe Auch

* Klasse [GeometryShape](../geometryshape)
* Schnittstelle [IAutoShape](../iautoshape)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: Shape
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 9520
url: /de/aspose.slides/shape/
---

## Shape-Klasse

Stellt eine Form auf einer Folie dar.

```csharp
public class Shape : IShape
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Eigenschaften zur Füllformatierung für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form versteckt ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den Hyperlink zurück oder setzt ihn, der für einen Mausklick definiert ist. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den Hyperlink zurück oder setzt ihn, der für Mouse-Over definiert ist. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option 'Als dekorativ kennzeichnen'. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur Lesezugriff Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Eigenschaften zur Linienformatierung für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linien-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie gegebenenfalls einen leeren String. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Form-ID im Folienkontext. Nur Lesezugriff UInt32. Siehe auch [`UniqueId`](./uniqueid) zum Abrufen der eindeutigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur Lesezugriff [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmen der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur Lesezugriff [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Form-ID im Präsentationskontext. Nur Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](./officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form im Hintergrund der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form im Vordergrund der Z-Reihenfolge zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und setzt die Platzhaltereigenschaften auf einen bestimmten Wert. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von Layout und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape für die Grenzen des Miniaturbilds wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt von Shape als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt von Shape als SVG-Datei. |

### Siehe auch

* Schnittstelle [IShape](../ishape)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
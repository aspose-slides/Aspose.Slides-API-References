---
title: IShape
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 6970
url: /de/aspose.slides/ishape/
---
## IShape Schnittstelle

Stellt eine Form auf einer Folie dar.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Gibt den alternativen Text zurück, der mit einer Form verknüpft ist, oder legt ihn fest. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück, der mit einer Form verknüpft ist, oder legt ihn fest. Lesen/Schreiben String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Ermöglicht das Abrufen der Basisschnittstelle IHyperlinkContainer. Nur-Lesen [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Ermöglicht das Abrufen der Basisschnittstelle ISlideComponent. Nur-Lesen [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus dargestellt wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur-Lesen Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesen [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-effekte enthält, die auf eine Form angewendet werden. Nur-Lesen [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füll-Formatierungs-Eigenschaften für eine Form enthält. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Ruft die Höhe der Form ab oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lesen/Schreiben Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Ruft die Option 'Als dekorativ markieren' ab oder legt sie fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesen Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder ist. Nur-Lesen Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linien-Formatierungs-Eigenschaften für eine Form enthält. Nur-Lesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der Form konstant bleibt und es PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur-Lesen UInt32. Siehe auch [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Nur-Lesen [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder legt sie fest. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesen [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das Linien-Formatierungs-Eigenschaften für eine Form enthält. Nur-Lesen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der von Add-Ins oder anderem Code verwendet werden kann. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als permanenter eindeutiger Schlüssel behandelt werden. Nur-Lesen UInt32. Siehe auch [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Ruft die Breite der Form ab oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Ruft die X-Koordinate der oberen linken Ecke der Form ab oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Ruft die Y-Koordinate der oberen linken Ecke der Form ab oder legt sie fest, gemessen in Punkten. Lesen/Schreiben Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] liefert die Form, die hinten in der Z-Reihenfolge liegt, und Shapes[Shapes.Count - 1] liefert die Form, die vorne liegt. Nur-Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt). Null wird zurückgegeben, wenn die aktuelle Form nicht vererbt wird. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Schnittstelle [IHyperlinkContainer](../ihyperlinkcontainer)
* Schnittstelle [ISlideComponent](../islidecomponent)
* Namensraum [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
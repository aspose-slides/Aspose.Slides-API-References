---
title: IShape
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 6950
url: /de/aspose.slides/ishape/
---
## IShape Schnittstelle

Stellt eine Form auf einer Folie dar.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Properties

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Gibt den Alternativtext zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese/Schreib String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Gibt den Titel des Alternativtexts zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese/Schreib String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Ermöglicht den Zugriff auf die Basis IHyperlinkContainer Schnittstelle. Nur lesend [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Ermöglicht den Zugriff auf die Basis ISlideComponent Schnittstelle. Nur lesend [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeige-Modus dargestellt wird. Lese/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte der Form zurück. Nur lesend Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesend [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Nur lesend [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält. Nur lesend [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lese/Schreib [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Liest oder legt die Höhe der Form fest, gemessen in Punkten. Lese/Schreib Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lese/Schreib Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Liest oder legt die Option 'Als dekorativ markieren' fest. Lese/Schreib Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesend Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder ist. Nur lesend Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. Nur lesend [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Lese/Schreib String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur lesend UInt32. Siehe auch [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesend [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Nur lesend [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Gibt die rohen Formrahmen-Eigenschaften zurück oder legt sie fest. Lese/Schreib [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Gibt die Drehung des angegebenen Form in Grad um die Z-Achse zurück oder legt sie fest. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lese/Schreib Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesend [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. Nur lesend [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel betrachtet werden. Nur lesend UInt32. Siehe auch [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Liest oder legt die Breite der Form fest, gemessen in Punkten. Lese/Schreib Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Liest oder legt die X-Koordinate der oberen linken Ecke der Form fest, gemessen in Punkten. Lese/Schreib Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Liest oder legt die Y-Koordinate der oberen linken Ecke der Form fest, gemessen in Punkten. Lese/Schreib Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am Anfang der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am Ende der Z-Reihenfolge zurück. Nur lesend Int32. |

## Methods

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt die Platzhalter-Eigenschaften auf einen angegebenen fest. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form erbt). Null wird zurückgegeben, wenn die aktuelle Form nicht geerbt wird. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Gibt das Miniaturbild der Form zurück. Der Standardwert für ShapeThumbnailBounds.Shape wird für die Miniaturbild-Grenzen verwendet. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### See Also

* Schnittstelle [IHyperlinkContainer](../ihyperlinkcontainer)
* Schnittstelle [ISlideComponent](../islidecomponent)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: IShape
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 6730
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
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt diesen, der mit einer Form verbunden ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt diesen, der mit einer Form verbunden ist. Lese-/Schreibzugriff String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Erlaubt den Zugriff auf die Basisschnittstelle IHyperlinkContainer. Nur lesend [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Erlaubt den Zugriff auf die Basisschnittstelle ISlideComponent. Nur lesend [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Die Eigenschaft spezifiziert, wie eine Form im Schwarzweiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur lesend Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesend [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf einer Form angewendeten Pixeleffekte enthält. Nur lesend [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Nur lesend [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder setzt diese. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt diese. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder setzt diese. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesend Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder ist. Nur lesend Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Nur lesend [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt diesen. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Erhält die einzigartige Form-ID im Folienkontext. Nur lesend UInt32. Siehe auch [`UniqueId`](./uniqueid) zum Erhalten der einzigartigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesend [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Nur lesend [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder setzt diese. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt diese, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an, ein negativer Wert eine Drehung gegen den Uhrzeigersinn. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesend [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Nur lesend [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Erhält die einzigartige Form-ID im Präsentationskontext. Nur lesend UInt32. Siehe auch [`OfficeInteropShapeId`](./officeinteropshapeid) zum Erhalten der einzigartigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt diese. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt diese. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt diese. Lese-/Schreibzugriff Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Reihenfolge zurück. Nur lesend Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls noch keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf die eines bestimmten. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ des Shapes thumbnail bounds ist standardmäßig ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Schnittstelle [IHyperlinkContainer](../ihyperlinkcontainer)
* Schnittstelle [ISlideComponent](../islidecomponent)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: IShape
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 6730
url: /de/aspose.slides/ishape/
---

## IShape-Schnittstelle

Stellt eine Form auf einer Folie dar.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff auf String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder setzt ihn, der mit einer Form verknüpft ist. Lese-/Schreibzugriff auf String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-IHyperlinkContainer-Schnittstelle. Schreibgeschützt [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Ermöglicht den Zugriff auf die Basis-ISlideComponent-Schnittstelle. Schreibgeschützt [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Schreibgeschützt Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Gibt die kundenspezifischen Daten der Form zurück. Schreibgeschützt [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewendeten Pixeleffekte enthält. Schreibgeschützt [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Schreibgeschützt [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Gibt die Höhe der Form zurück oder setzt sie. Lese-/Schreibzugriff auf Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff auf Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder setzt sie. Lese-/Schreibzugriff auf Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Schreibgeschützt Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bestimmt, ob die Form ein Texthalter ist. Schreibgeschützt Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Schreibgeschützt [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Gibt den Namen einer Form zurück oder setzt ihn. Lese-/Schreibzugriff auf String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Gibt die eindeutige Form-ID im Folienbereich zurück. Schreibgeschützt UInt32. Siehe auch [`UniqueId`](./uniqueid) zum Abrufen der eindeutigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Schreibgeschützt [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Schreibgeschützt [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Gibt die Rohdaten des Rahmen der Form zurück oder setzt sie. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder setzt sie, um die eine bestimmte Form um die z-Achse gedreht ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff auf Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Schreibgeschützt [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Gibt die eindeutige Form-ID im Präsentationsbereich zurück. Schreibgeschützt UInt32. Siehe auch [`OfficeInteropShapeId`](./officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Folienbereich. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Gibt die Breite der Form zurück oder setzt sie. Lese-/Schreibzugriff auf Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff auf Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder setzt sie. Lese-/Schreibzugriff auf Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form an der Vorderseite der Z-Reihenfolge zurück. Schreibgeschützt Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf eine bestimmte. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von Layout und/oder Masterfolie, von der die aktuelle Form abgeleitet ist). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapesThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Schnittstelle [IHyperlinkContainer](../ihyperlinkcontainer)
* Schnittstelle [ISlideComponent](../islidecomponent)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
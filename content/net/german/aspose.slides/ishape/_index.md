---
title: IShape
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
weight: 6400
url: /de/aspose.slides/ishape/
---
## IShape interface

Stellt eine Form auf einer Folie dar.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Gibt den einer Form zugeordneten alternativen Text zurück oder legt ihn fest. Lesen/SchreibenString . |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder legt ihn fest. Lesen/SchreibenString . |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Ermöglicht das Abrufen der Basis-IHyperlinkContainer-Schnittstelle. Schreibgeschützt[`IHyperlinkContainer`](../ihyperlinkcontainer) . |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Ermöglicht das Abrufen der Basis-ISlideComponent-Schnittstelle. Schreibgeschützt[`ISlideComponent`](../islidecomponent) . |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | -Eigenschaft gibt an, wie eine Form im Schwarzweiß-Anzeigemodus gerendert wird.. Lesen/Schreiben[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen in der Form zurück. SchreibgeschütztInt32 . |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das auf eine Form angewendete Pixeleffekte enthält. Schreibgeschützt[`IEffectFormat`](../ieffectformat) . |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lesen/SchreibenBoolean . |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. SchreibgeschütztBoolean . |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bestimmt, ob die Form TextHolder ist. SchreibgeschütztBoolean . |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Schreibgeschützt[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Lesen/SchreibenString . |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Ruft eine eindeutige Formkennung im Folienbereich ab. SchreibgeschütztUInt32 . Siehe auch[`UniqueId`](./uniqueid) zum Abrufen einer eindeutigen Formkennung im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Schreibgeschützt[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Schreibgeschützt[`IPlaceholder`](../iplaceholder) . |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohformrahmens zurück oder legt sie fest. Lesen/Schreiben[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Gibt die Gradzahl zurück, um die die angegebene Form um die z-Achse gedreht wird, oder legt sie fest. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lesen/SchreibenSingle . |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Gibt die Sperren der Form zurück. Schreibgeschützt[`IBaseShapeLock`](../ibaseshapelock) . |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das Zeilenformatierungseigenschaften für eine Form enthält. Schreibgeschützt[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Ruft eine eindeutige Formkennung im Darstellungsbereich ab. SchreibgeschütztUInt32 . Siehe auch[`OfficeInteropShapeId`](./officeinteropshapeid) zum Abrufen einer eindeutigen Formkennung im Folienbereich. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [X](../../aspose.slides/ishape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/SchreibenSingle . |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am Anfang der Z-Reihenfolge zurück. order. SchreibgeschütztInt32 . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail)() | Gibt Form-Miniaturansicht zurück. ShapeThumbnailBounds.Shape Form-Miniatur-Umgrenzungstyp wird standardmäßig verwendet. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail_1)(ShapeThumbnailBounds, float, float) | Gibt Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Speichert den Inhalt von Shape als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Speichert den Inhalt von Shape als SVG-Datei. |

### Siehe auch

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

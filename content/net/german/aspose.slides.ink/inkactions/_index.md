---
title: InkActions
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt die Wurzel der Tintenaktionen dar.
type: docs
weight: 7330
url: /de/aspose.slides.ink/inkactions/
---

## InkActions-Klasse

Stellt die Wurzel der Tintenaktionen dar.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verbunden ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des mit einer Form verbundenen alternativen Textes zurück oder legt ihn fest. Lese-/Schreibzugriff String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur-Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesezugriff [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die auf eine Form angewandten Pixeleffekte enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur-Lesezugriff [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur-Lesezugriff [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmens der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesezugriff [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lesezugriff [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreibzugriff [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder legt die Option "Als dekorativ markieren" fest. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-Lesezugriff Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linien-Eigenschaften haben, null zurückgeben. Nur-Lesezugriff [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie einen leeren String, wenn nötig. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Bezeichner der Form im Folienbereich. Nur-Lesezugriff UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) zum Abrufen der eindeutigen Bezeichner der Form im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls null. Nur-Lesezugriff [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lesezugriff [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lesezugriff [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmens der Form zurück oder legt sie fest. Lese-/Schreibzugriff [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht wird. Ein positiver Wert bedeutet eine Drehung im Uhrzeigersinn; ein negativer Wert bedeutet eine Drehung gegen den Uhrzeigersinn. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lesezugriff [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lesezugriff [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-Lesezugriff [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Bezeichner der Form im Präsentationsbereich. Nur-Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) zum Abrufen der eindeutigen Bezeichner der Form im Folienbereich. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der Z-Reihenfolge zurück. Nur-Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und legt die Platzhaltereigenschaften auf eine angegebene fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form erbt). Ein null wird zurückgegeben, wenn die aktuelle Form nicht vererbt wird. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. ShapeThumbnailBounds.Shape-Miniaturbildgrenzwerttyp wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* Schnittstelle [IInkActions](../iinkactions)
* Namensraum [Aspose.Slides.Ink](../../aspose.slides.ink)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
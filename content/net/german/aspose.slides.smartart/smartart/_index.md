---
title: SmartArt
second_title: Aspose.Sildes für .NET API Referenz
description: Bezeichnet ein SmartArt-Diagramm
type: docs
weight: 10290
url: /de/aspose.slides.smartart/smartart/
---

## SmartArt-Klasse

Bezeichnet ein SmartArt-Diagramm

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück. Nur-Lese [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreib-String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreib-String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreib [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Gibt den Farbstil des SmartArt-Objekts zurück oder legt ihn fest. Lese-/Schreib [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur-Lese Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lese [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Effekt-Eigenschaften haben. Nur-Lese [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Füll-Eigenschaften haben. Nur-Lese [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lese-/Schreib Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lese [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für die Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder setzt die Option „Als dekorativ markieren“ Lese-/Schreib Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lese Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Gibt den Zustand des SmartArt-Diagramms in Bezug auf (von links nach rechts) LTR oder (von rechts nach links) RTL zurück oder legt ihn fest, wenn das Diagramm eine Umkehrung unterstützt. Lese-/Schreib Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur-Lese Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Gibt das Layout des SmartArt-Objekts zurück oder legt es fest. Lese-/Schreib [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine Linien-Eigenschaften haben. Nur-Lese [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie den leeren Stringwert, wenn nötig. Lese-/Schreib String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Gibt Sammlungen von Wurzknoten im SmartArt-Objekt zurück. Nur-Lese [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Form-ID im Folienbereich. Nur-Lese UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) zum Abrufen der eindeutigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lese [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lese [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Gibt den Schnellstil des SmartArt-Objekts zurück oder legt ihn fest. Lese-/Schreib [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Rohrahmen-Eigenschaften der Form zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die eine bestimmte Form um die z-Achse rotiert ist. Ein positiver Wert deutet auf eine Drehung im Uhrzeigersinn hin; ein negativer Wert deutet auf eine Drehung gegen den Uhrzeigersinn hin. Lese-/Schreib Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lese [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: kann null für bestimmte Arten von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur-Lese [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Form-ID im Präsentationsbereich. Nur-Lese UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Folienbereich. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Reihenfolge zurück. Nur-Lese Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Platzhaltereigenschaften auf eine angegebene fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine Grundplatzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Ein Nullwert wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Thumbnail der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Thumbnail der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe Auch

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* Schnittstelle [ISmartArt](../ismartart)
* Namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
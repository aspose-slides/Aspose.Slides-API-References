---
title: SmartArt
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein SmartArt-Diagramm dar
type: docs
weight: 10290
url: /de/aspose.slides.smartart/smartart/
---

## SmartArt-Klasse

Stellt ein SmartArt-Diagramm dar

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Gibt Sammlungen aller Knoten im SmartArt-Objekt zurück. Nur-lesend [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt diesen für eine Form fest. Schreib-/Lesezeichen. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder legt diesen für eine Form fest. Schreib-/Lesezeichen. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Schreib-/Lesezeichen [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Gibt den Farbstil des SmartArt-Objekts zurück oder legt diesen fest. Schreib-/Lesezeichen [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur-lesend Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-lesend [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die Anwendung von Pixeleffekten auf eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur-lesend [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur-lesend [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Schreib-/Lesezeichen [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-lesend [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form versteckt ist. Schreib-/Lesezeichen Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Schreib-/Lesezeichen [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-lesend [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder legt ihn fest. Schreib-/Lesezeichen [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder legt sie fest. Schreib-/Lesezeichen Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-lesend Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Gibt den Zustand des SmartArt-Diagramms hinsichtlich (von links nach rechts) LTR oder (von rechts nach links) RTL zurück oder legt ihn fest, wenn das Diagramm eine Umkehrung unterstützt. Schreib-/Lesezeichen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur-lesend Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Gibt das Layout des SmartArt-Objekts zurück oder legt es fest. Schreib-/Lesezeichen [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linieneigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Linien-Eigenschaften haben, null zurückgeben. Nur-lesend [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie leeren String, falls erforderlich. Schreib-/Lesezeichen String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Gibt Sammlungen von Wurzelknoten im SmartArt-Objekt zurück. Nur-lesend [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Form-ID im Folienkontext zurück. Nur-lesend UInt32. Siehe auch [`UniqueId`](../../aspose.slides/shape/uniqueid) zum Abrufen der eindeutigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-lesend [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-lesend [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-lesend [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Gibt den Schnellstil des SmartArt-Objekts zurück oder legt ihn fest. Schreib-/Lesezeichen [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Formrahmens zurück oder legt sie fest. Schreib-/Lesezeichen [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse gedreht wird. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Schreib-/Lesezeichen Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-lesend [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-lesend [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-lesend [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Form-ID im Präsentationskontext zurück. Nur-lesend UInt32. Siehe auch [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) zum Abrufen der eindeutigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form im z-Ordnung zurück. Shapes[0] gibt die Form hinten in der z-Ordnung zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Ordnung zurück. Nur-lesend Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Eigenschaften des Platzhalters auf einen bestimmten fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (eine Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. ShapeThumbnailBounds.Shape-miniaturansichtsgrenzwerttyp wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* Schnittstelle [ISmartArt](../ismartart)
* Namensraum [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* Assembly [Aspose.Slides](../../) 

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
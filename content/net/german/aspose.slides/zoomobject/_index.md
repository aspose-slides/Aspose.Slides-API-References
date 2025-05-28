---
title: ZoomObject
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein Zoom-Objekt in einer Folie dar.
type: docs
weight: 11560
url: /de/aspose.slides/zoomobject/
---

## ZoomObject-Klasse

Stellt ein Zoom-Objekt in einer Folie dar.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den mit einer Form verbundenen alternativen Text zurück oder legt ihn fest. Lese-/Schreibzeichenfolge. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des mit einer Form verbundenen alternativen Texts zurück oder legt ihn fest. Lese-/Schreibzeichenfolge. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft, die angibt, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungsstellen an der Form zurück. Nur-Lese Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lese [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: Kann für bestimmte Arten von Formen, die keine Effekt-Eigenschaften haben, null zurückgeben. Nur-Lese [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Füll-Eigenschaften haben, null zurückgeben. Nur-Lese [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formularrahmens zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreib Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lese [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Holt oder legt den Bildtyp eines Zoom-Objekts fest. Lese-/Schreib [`ZoomImageType`](../zoomimagetype). Standardwert: Vorschau |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Holt oder legt die Option 'Als dekorativ markieren' fest. Lese-/Schreib Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lese Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur-Lese Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine Linieneigenschaften haben, null zurückgeben. Nur-Lese [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie einen leeren String, wenn nötig. Lese-/Schreibzeichenfolge. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Holt die eindeutige Form-ID im Folienkontext. Nur-Lese UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für den Erhalt der eindeutigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lese [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lese [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Holt oder legt das Navigationsverhalten im Präsentationsmodus fest. Lese-/Schreib Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die z-Achse gedreht ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreib Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Holt oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Ziel-Folie verwenden soll. Lese-/Schreib Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lese [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann für bestimmte Arten von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-Lese [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Holt oder legt die Dauer des Übergangs zwischen Zoom und Folie fest. Lese-/Schreib Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Holt die eindeutige Form-ID im Präsentationskontext. Nur-Lese UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für den Erhalt der eindeutigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Holt oder legt das Bild für das Zoom-Objekt fest. Lese-/Schreib [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form vorne in der z-Reihenfolge zurück. Nur-Lese Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn es keinen gibt, und legt die Eigenschaften des Platzhalters auf einen bestimmten fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder Master-Folie, von der die aktuelle Form abgeleitet ist). Ein Nullwert wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../graphicalobject)
* Schnittstelle [IZoomObject](../izoomobject)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
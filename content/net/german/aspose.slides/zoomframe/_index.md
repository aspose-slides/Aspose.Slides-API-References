---
title: ZoomFrame
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt ein Slide Zoom-Objekt in einer Folie dar.
type: docs
weight: 11530
url: /de/aspose.slides/zoomframe/
---

## ZoomFrame-Klasse

Stellt ein Slide Zoom-Objekt in einer Folie dar.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verbunden ist. Lesen/Schreiben String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Textes zurück oder legt ihn fest, der mit einer Form verbunden ist. Lesen/Schreiben String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschaft, die angibt, wie eine Form im Schwarzweiß-Anzeigemodus gerendert wird. Lesen/Schreiben [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Anschlussstellen an der Form zurück. Nur lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: Kann null für bestimmte Arten von Formen zurückgeben, die keine Effekt-Eigenschaften haben. Nur lesen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Arten von Formen zurückgeben, die keine Füll-Eigenschaften haben. Nur lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lesen/Schreiben Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Gibt den Bildtyp eines Zoom-Objekts zurück oder legt ihn fest. Lesen/Schreiben [`ZoomImageType`](../zoomimagetype). Standardwert: Vorschau |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder legt sie fest. Lesen/Schreiben Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur lesen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Arten von Formen zurückgeben, die keine Linieneigenschaften haben. Nur lesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Muss nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lesen/Schreiben String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Form-ID im Folienkontext zurück. Nur lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für das Abrufen der eindeutigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die rohen Eigenschaften des Formrahmens zurück oder legt sie fest. Lesen/Schreiben [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Gibt das Navigationsverhalten in der Diashow zurück oder legt es fest. Lesen/Schreiben Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert gibt eine Drehung im Uhrzeigersinn an; ein negativer Wert gibt eine Drehung gegen den Uhrzeigersinn an. Lesen/Schreiben Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Gibt den Wert zurück oder legt ihn fest, der angibt, ob der Zoom den Hintergrund der Ziel-Folie verwenden soll. Lesen/Schreiben Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesen [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Gibt das Folienobjekt zurück oder legt es fest, auf das das Slide Zoom-Objekt verweist. Lesen/Schreiben [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Arten von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur lesen [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Gibt die Dauer der Übergänge zwischen Zoom und Folie zurück oder legt sie fest. Lesen/Schreiben Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Form-ID im Präsentationskontext zurück. Nur lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für das Abrufen der eindeutigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lesen/Schreiben Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Gibt das Bild für das Zoom-Objekt zurück oder legt es fest. Lesen/Schreiben [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der Z-Reihenfolge zurück. Nur lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn noch keiner vorhanden ist, und legt die Eigenschaften des Platzhalters auf einen bestimmten fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (eine Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Ein null wird zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe Auch

* Klasse [ZoomObject](../zoomobject)
* Schnittstelle [IZoomFrame](../izoomframe)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
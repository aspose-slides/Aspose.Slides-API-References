---
title: ZoomObject
second_title: Aspose.Slides für .NET API Referenz
description: Repräsentiert ein Zoom-Objekt in einer Folie.
type: docs
weight: 11560
url: /de/aspose.slides/zoomobject/
---

## ZoomObject-Klasse

Repräsentiert ein Zoom-Objekt in einer Folie.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den mit einer Form verknüpften alternativen Text zurück oder legt ihn fest. Schreib-/Lesezeichen String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des mit einer Form verknüpften alternativen Texts zurück oder legt ihn fest. Schreib-/Lesezeichen String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Schreib-/Lesezeichen [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte an der Form zurück. Nur-Lese Integer. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lese [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte enthält, die auf eine Form angewendet wurden. Hinweis: kann für bestimmte Typen von Formen, die keine Effekteigenschaften haben, null zurückgeben. Nur-Lese [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Füllebenen haben, null zurückgeben. Nur-Lese [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt sie fest. Schreib-/Lesezeichen [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Schreib-/Lesezeichen Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt ihn fest. Schreib-/Lesezeichen [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur-Lese [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder legt ihn fest. Schreib-/Lesezeichen [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Ruft den Bildtyp eines Zoom-Objekts ab oder legt ihn fest. Schreib-/Lesezeichen [`ZoomImageType`](../zoomimagetype). Standardwert: Vorschau |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ruft die Option 'Als dekorativ markieren' ab oder legt sie fest. Schreib-/Lesezeichen Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lese Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur-Lese Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine Linieigenschaften haben, null zurückgeben. Nur-Lese [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Darf nicht null sein. Verwenden Sie einen leeren String, wenn nötig. Schreib-/Lesezeichen String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft die eindeutige Form-ID im Folienbereich ab. Nur-Lese UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) zum Abrufen der einzigartigen Form-ID im Präsentationsbereich. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lese [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lese [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des rohen Formrahmens zurück oder legt sie fest. Schreib-/Lesezeichen [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Ruft das Navigationverhalten in der Diashow ab oder legt es fest. Schreib-/Lesezeichen Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse gedreht wird. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Schreib-/Lesezeichen Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur-Lese [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob der Zoom den Hintergrund der Ziel-Folie verwenden soll. Schreib-/Lesezeichen Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur-Lese [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: kann für bestimmte Typen von Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur-Lese [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Ruft die Dauer der Transition zwischen Zoom und Folie ab oder legt sie fest. Schreib-/Lesezeichen Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft die eindeutige Form-ID im Präsentationsbereich ab. Nur-Lese UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) zum Abrufen der einzigartigen Form-ID im Folienbereich. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Schreib-/Lesezeichen Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Ruft das Bild für das Zoom-Objekt ab oder legt es fest. Schreib-/Lesezeichen [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form zurück, die sich hinten in der Z-Reihenfolge befindet, und Shapes[Shapes.Count - 1] gibt die Form zurück, die sich vorne in der Z-Reihenfolge befindet. Nur-Lese Integer. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Platzhaftereigenschaften auf einen angegebenen fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine Grundform des Platzhalters zurück (Form von dem Layout und/oder Master-Folie, von der die aktuelle Form abgeleitet ist). Es wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Miniaturansicht der Form zurück. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Miniaturansicht der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../graphicalobject)
* Schnittstelle [IZoomObject](../izoomobject)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
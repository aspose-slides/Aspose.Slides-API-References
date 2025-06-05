---
title: SummaryZoomFrame
second_title: Aspose.Slides für .NET API Referenz
description: Stellt ein Summary Zoom-Objekt in einer Folie dar.
type: docs
weight: 10460
url: /de/aspose.slides/summaryzoomframe/
---

## SummaryZoomFrame-Klasse

Stellt ein Summary Zoom-Objekt in einer Folie dar.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt ihn fest, der mit einer Form verknüpft ist. Lese-/Schreib String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des mit einer Form verknüpften alternativen Textes zurück oder legt ihn fest. Lese-/Schreib String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Displaymodus gerendert wird. Lese-/Schreib [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Anschlusspunkte auf der Form zurück. Nur lesen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur lesen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das die Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: kann für bestimmte Formen, die keine Effekteigenschaften haben, null zurückgeben. Nur lesen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Füllungseigenschaften haben, null zurückgeben. Nur lesen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Rahmen der Form zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form versteckt ist. Lese-/Schreib Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder legt ihn fest. Lese-/Schreib [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ruft die Option „Als dekorativ markieren“ ab oder legt sie fest. Lese-/Schreib Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur lesen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur lesen Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | Ruft das Layout der Summary Zoom-Abschnitte im Rahmen ab. Der Standardwert ist GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine Linieneigenschaften haben, null zurückgeben. Nur lesen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt ihn fest. Muss nicht null sein. Verwenden Sie den leeren Stringwert, wenn nötig. Lese-/Schreib String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Ruft die eindeutige Form-ID im Folienkontext ab. Nur lesen UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für das Abrufen der eindeutigen Form-ID im Präsentationskontext. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohrahmens der Form zurück oder legt sie fest. Lese-/Schreib [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt sie fest, um die die angegebene Form um die Z-Achse rotiert ist. Ein positiver Wert weist auf eine Drehung im Uhrzeigersinn hin; ein negativer Wert weist auf eine Drehung gegen den Uhrzeigersinn hin. Lese-/Schreib Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur lesen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur lesen [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | Ruft [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) für das Summary Zoom Frame-Objekt ab. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: kann für bestimmte Formen, die keine 3D-Eigenschaften haben, null zurückgeben. Nur lesen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Ruft die eindeutige Form-ID im Präsentationskontext ab. Nur lesen UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für das Abrufen der eindeutigen Form-ID im Folienkontext. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest. Lese-/Schreib Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der z-Reihenfolge zurück. Shapes[0] gibt die Form ganz hinten in der z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der z-Reihenfolge zurück. Nur lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Eigenschaften des Platzhalters auf einen bestimmten Wert fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine Basis-Platzhalterform zurück (eine Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form abgeleitet ist). Wird null zurückgegeben, wenn die aktuelle Form nicht abgeleitet ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt die Thumbnail-Darstellung der Form zurück. Der ShapeThumbnailBounds.Shape Thumbnail-Grenzwerttyp wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt die Thumbnail-Darstellung der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [GraphicalObject](../graphicalobject)
* Schnittstelle [ISummaryZoomFrame](../isummaryzoomframe)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
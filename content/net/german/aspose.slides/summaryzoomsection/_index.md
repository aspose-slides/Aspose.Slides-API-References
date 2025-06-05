---
title: SummaryZoomSection
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Rahmen dar.
type: docs
weight: 10470
url: /de/aspose.slides/summaryzoomsection/
---

## SummaryZoomSection-Klasse

Stellt ein Summary Zoom Section-Objekt in einem Summary Zoom-Rahmen dar.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Gibt den alternativen Text zurück oder legt diesen fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff auf String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Gibt den Titel des alternativen Texts zurück oder legt diesen fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff auf String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff auf [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Gibt die Anzahl der Verbindungspunkte auf der Form zurück. Nur Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Gibt die benutzerdefinierten Daten der Form zurück. Nur Lesezugriff auf [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Gibt die textliche Beschreibung des Summary Zoom Section-Objekts zurück. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine Effekteigenschaften haben. Nur Lesezugriff auf [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Gibt das FillFormat-Objekt zurück, das Formatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine Füllungseigenschaften haben. Nur Lesezugriff auf [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Gibt die Eigenschaften des Formrahmens zurück oder legt diese fest. Lese-/Schreibzugriff auf [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff auf [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Gibt die Höhe der Form zurück oder legt diese fest. Lese-/Schreibzugriff auf Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form verborgen ist. Lese-/Schreibzugriff auf Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Gibt den für einen Mausklick definierten Hyperlink zurück oder legt diesen fest. Lese-/Schreibzugriff auf [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Gibt den Hyperlink-Manager zurück. Nur Lesezugriff auf [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Gibt den für die Mouseover definierte Hyperlink zurück oder legt diesen fest. Lese-/Schreibzugriff auf [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Gibt den Bildtyp eines Zoom-Objekts zurück oder legt diesen fest. Lese-/Schreibzugriff auf [`ZoomImageType`](../zoomimagetype). Standardwert: Vorschau |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Gibt die Option 'Als dekorativ markieren' zurück oder legt diese fest. Lese-/Schreibzugriff auf Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur Lesezugriff auf Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form ein TextHolder_PPT ist. Nur Lesezugriff auf Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine Linieneigenschaften haben. Nur Lesezugriff auf [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Gibt den Namen einer Form zurück oder legt diesen fest. Darf nicht null sein. Verwenden Sie einen leeren String, wenn nötig. Lese-/Schreibzugriff auf String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gibt die eindeutige Identifikation der Form im Zusammenhang mit der Folie zurück. Nur Lesezugriff auf UInt32. Siehe auch [`UniqueId`](../shape/uniqueid) für die eindeutige Identifikation der Form im Zusammenhang mit der Präsentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur Lesezugriff auf [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur Lesezugriff auf [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Gibt die übergeordnete Präsentation einer Folie zurück. Nur Lesezugriff auf [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Gibt die Eigenschaften des Rohformrahmens zurück oder legt diese fest. Lese-/Schreibzugriff auf [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Gibt das Navigationsverhalten im Präsentationsmodus zurück oder legt dieses fest. Lese-/Schreibzugriff auf Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Gibt die Anzahl der Grad zurück oder legt diese fest, um die die angegebene Form um die z-Achse rotiert ist. Ein positiver Wert zeigt eine Drehung im Uhrzeigersinn an; ein negativer Wert zeigt eine Drehung gegen den Uhrzeigersinn an. Lese-/Schreibzugriff auf Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Gibt die Sperren der Form zurück. Nur Lesezugriff auf [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Gibt den Wert zurück oder legt diesen fest, der angibt, ob der Zoom den Hintergrund der Ziel-Folie verwenden soll. Lese-/Schreibzugriff auf Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Gibt die übergeordnete Folie einer Form zurück. Nur Lesezugriff auf [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Gibt das Abschnittsobjekt zurück oder legt dieses fest, zu dem das Section Zoom-Objekt verlinkt ist. Lese-/Schreibzugriff auf [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekt-Eigenschaften für eine Form enthält. Hinweis: Kann null für bestimmte Typen von Formen zurückgeben, die keine 3D-Eigenschaften haben. Nur Lesezugriff auf [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Gibt den textlichen Titel des Summary Zoom Section-Objekts zurück. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Gibt die Dauer der Übergangs zwischen Zoom und Folie zurück oder legt diese fest. Lese-/Schreibzugriff auf Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gibt die eindeutige Identifikation der Form im Zusammenhang mit der Präsentation zurück. Nur Lesezugriff auf UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid) für die eindeutige Identifikation der Form im Zusammenhang mit der Folie. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Gibt die Breite der Form zurück oder legt diese fest. Lese-/Schreibzugriff auf Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Gibt die x-Koordinate der oberen linken Ecke der Form zurück oder legt diese fest. Lese-/Schreibzugriff auf Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Gibt die y-Koordinate der oberen linken Ecke der Form zurück oder legt diese fest. Lese-/Schreibzugriff auf Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Gibt das Bild für das Zoom-Objekt zurück oder legt dieses fest. Lese-/Schreibzugriff auf [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form ganz hinten in der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form ganz vorne in der Z-Reihenfolge zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, wenn keiner vorhanden ist, und legt die Eigenschaften des Platzhalters auf einen bestimmten fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Gibt eine grundlegende Platzhalterform zurück (Form von der Layout- und/oder Masterfolie, von der die aktuelle Form erbt). Wird null zurückgegeben, wenn die aktuelle Form nicht erbt. |
| [GetImage](../../aspose.slides/shape/getimage)() | Gibt das Miniaturbild der Form zurück. Standardmäßig wird der ShapeThumbnailBounds.Shape verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Gibt das Miniaturbild der Form zurück. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bestimmt, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [SectionZoomFrame](../sectionzoomframe)
* Schnittstelle [ISummaryZoomSection](../isummaryzoomsection)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
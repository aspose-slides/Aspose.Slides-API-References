---
title: SectionZoomFrame
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein Section Zoom-Objekt in einer Folie dar.
type: docs
weight: 9800
url: /de/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame Klasse

Stellt ein Section Zoom-Objekt in einer Folie dar.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Liefert oder legt den alternativen Text fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Liefert oder legt den Titel des alternativen Textes fest, der mit einer Form verknüpft ist. Lese-/Schreibzugriff String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Die Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird. Lese-/Schreibzugriff [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Liefert die Anzahl der Verbindungsstellen der Form. Nur-Lesezugriff Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Liefert die benutzerdefinierten Daten der Form. Nur-Lesezugriff [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Liefert das EffectFormat-Objekt, das Pixeleffekte enthält, die auf eine Form angewendet werden. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen. Nur-Lesezugriff [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Liefert das FillFormat-Objekt, das Füllformatierungs-Eigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen. Nur-Lesezugriff [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Liefert oder legt die Eigenschaften des Formrahmens fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Liefert die Sperren der Form. Nur-Lesezugriff [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Liefert oder legt die Höhe der Form fest, gemessen in Punkten. Lese-/Schreibzugriff Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestimmt, ob die Form ausgeblendet ist. Lese-/Schreibzugriff Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Liefert oder legt den für Mausklick definierten Hyperlink fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Liefert den Hyperlink-Manager. Nur-Lesezugriff [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Liefert oder legt den für Maus-over definierten Hyperlink fest. Lese-/Schreibzugriff [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Liefert oder legt den Bildtyp eines Zoom-Objekts fest. Lese-/Schreibzugriff [`ZoomImageType`](../zoomimagetype). Standardwert: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Liefert oder legt die Option ‘Als dekorativ markieren’ fest. Lese-/Schreibzugriff Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestimmt, ob die Form gruppiert ist. Nur-Lesezugriff Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestimmt, ob die Form TextHolder_PPT ist. Nur-Lesezugriff Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Liefert das LineFormat-Objekt, das Linieneigenschaften für eine Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine Linien-Eigenschaften besitzen. Nur-Lesezugriff [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Liefert oder legt den Namen einer Form fest. Darf nicht null sein. Bei Bedarf leere Zeichenkette verwenden. Lese-/Schreibzugriff String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Liefert einen folienbezogenen eindeutigen Bezeichner, der für die Lebensdauer der Form konstant bleibt und es PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur-Lesezugriff UInt32. Siehe auch [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Liefert das übergeordnete GroupShape-Objekt, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lesezugriff [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Liefert den Platzhalter für eine Form. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lesezugriff [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Liefert die übergeordnete Präsentation einer Folie. Nur-Lesezugriff [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Liefert oder legt die rohen Eigenschaften des Formrahmens fest. Lese-/Schreibzugriff [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Liefert oder legt das Navigationsverhalten in der Diashow fest. Lese-/Schreibzugriff Boolean. Standardwert: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Liefert oder legt die Anzahl der Grad fest, um die die angegebene Form um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lese-/Schreibzugriff Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Liefert die Sperren der Form. Nur-Lesezugriff [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 Eigenschaften) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Liefert oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Ziel-Folie verwendet. Lese-/Schreibzugriff Boolean. Standardwert: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Liefert die übergeordnete Folie einer Form. Nur-Lesezugriff [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Liefert oder legt das Abschnittsobjekt fest, auf das das Section-Zoom-Objekt verlinkt. Lese-/Schreibzugriff [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Liefert das ThreeDFormat-Objekt, das 3D-Effekteigenschaften einer Form enthält. Hinweis: Kann null zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen. Nur-Lesezugriff [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Liefert oder legt die Dauer des Übergangs zwischen Zoom und Folie fest. Lese-/Schreibzugriff Single. Standardwert: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Liefert einen internen, präsentationsbezogenen Bezeichner, der für Add-ins oder anderen Code bestimmt ist. Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als dauerhaft eindeutiger Schlüssel behandelt werden. Nur-Lesezugriff UInt32. Siehe auch [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Liefert oder legt die Breite der Form fest, gemessen in Punkten. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Liefert oder legt die X-Koordinate der oberen linken Ecke der Form fest, gemessen in Punkten. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Liefert oder legt die Y-Koordinate der oberen linken Ecke der Form fest, gemessen in Punkten. Lese-/Schreibzugriff Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Liefert oder legt das Bild für das Zoom-Objekt fest. Lese-/Schreibzugriff [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Liefert die Position einer Form in der Z-Reihenfolge. Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück, und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende zurück. Nur-Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt die Platzhalter-Eigenschaften auf einen angegebenen fest. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Liefert eine grundlegende Platzhalterform (Form aus dem Layout und/oder der Master-Folie, von der die aktuelle Form ererbt wird). Null wird zurückgegeben, wenn die aktuelle Form nicht vererbt ist. |
| [GetImage](../../aspose.slides/shape/getimage)() | Liefert das Miniaturbild der Form. Der Typ ShapeThumbnailBounds.Shape wird standardmäßig verwendet. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Liefert das Miniaturbild der Form. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Liefert die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiert, dass diese Form kein Platzhalter ist. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Speichert den Inhalt der Form als SVG-Datei. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Speichert den Inhalt der Form als SVG-Datei. |

### Siehe auch

* Klasse [ZoomObject](../zoomobject)
* Schnittstelle [ISectionZoomFrame](../isectionzoomframe)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->